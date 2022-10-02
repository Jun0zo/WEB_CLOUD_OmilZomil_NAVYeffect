
# ReadME

사람인식, 두발상태확인, 복장분류, 복장상태확인 순으로

```mermaid

graph LR

A[사람인식] --> B[두발상태확인] --> C[복장분류] --> D[복장상태확인]
```


### 1. 사람인식
Yolo를 이용한다. 
  

### 3. 두발상태 확인
	

### 4. 복장분류

### 5. 복장상태확인

Morphology연산과 MS COCO dataset으로 학습한 HED(Holistically-Nested Edge Detection)으로 외곽선을 구한다. 

| ![HED sample](https://blog.kakaocdn.net/dn/kHShf/btrsTcrSSL1/9vi4F5h9lB2jn0H4qdl5Mk/img.jpg) | 
|:--:| 
| *HED Sample* |


Dataset
[Pascal VOC Dataset Mirror (pjreddie.com)](https://pjreddie.com/projects/pascal-voc-dataset-mirror/)
	[COCO - Common Objects in Context (cocodataset.org)](https://cocodataset.org/#home)

Reference

  [[1504.06375] Holistically-Nested Edge Detection (arxiv.org)](https://arxiv.org/abs/1504.06375)
