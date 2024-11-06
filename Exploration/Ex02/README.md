# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 윤수영
- 리뷰어 : 김하영


# PRT(Peer Review Template)
- [o]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물 모델이 평가지표 RMSE결과치 첨부함
  
      ![image](https://github.com/user-attachments/assets/1146c5be-4f44-40c7-8479-e4ec8853024b)

    
- [o]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 프로젝트를 위해 데이터 EDA부터 전처리 및 모델링 과정에 따라 코드를 블럭화하여 진행함
    - 해당 코드의 기능 및 코드에 대한 예상 및 결과를 기술하여 해당코드이 목적에 대해 이해가 잘됨
    - 데이터의전처리 과정에서 다양한 그래프를 사용하여 코드와 그 결과 모두 이해하기 좋았음
  
    ![image](https://github.com/user-attachments/assets/88d499ac-a8ae-4f8d-aee3-ae7aa2a4b63b)
     ![image](https://github.com/user-attachments/assets/a4f03a6d-9f62-41cb-a485-a31fde1262b8)
    ![image](https://github.com/user-attachments/assets/ec1b5772-5714-44be-aa59-fd66b7ee3bbe)

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 데이터 전처리를 위해 다양한 시도를 하였음. 특히 데이터를 범주형으로 타입을 변경하는 시도 중 Date속성을 년, 월, 일로 범주화함.
    - 이와 관련하여 '월'이라는 피처가 아파트 값과 상관관계가 있다는 인사이트를 발견함.
    - 프로젝트를 통해 모델 성능 개선을 위한 시도 중 하나로 다양한 파라미터 변경을 시도하고 결과치를 확인하였음
      
   ![image](https://github.com/user-attachments/assets/9d5b7611-ac95-4809-9edb-fbed05ec3d4f)
   ![image](https://github.com/user-attachments/assets/dbedc15a-2adf-4386-98ef-5330219f917f)
   ![image](https://github.com/user-attachments/assets/0494bc6b-e157-4770-8522-f1df5e89f703)
   ![image](https://github.com/user-attachments/assets/f138d548-4c02-474c-928e-fae9cfa2679e)
   ![image](https://github.com/user-attachments/assets/a2f399f7-3969-48e7-8575-84ee503f23d8)

         
- [ ]  **4. 회고를 잘 작성했나요?**
    - 블럭 코드별로 데이터를 살펴본 결과 등의 회고기록이 있음
    - 전체 코드 실행 플로우가 있으면 좋을 것 같음
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 다시 사용될 수 있는 알로리즘은 함수화하여 효율성을 높였음.
    - 전반적으로 코드가 간결하여 직관적으로 이해가 잘되었음

     ![image](https://github.com/user-attachments/assets/8160333f-958e-40a0-ad5d-fca8a46a4a86)


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어 회고: 수영님의 코드에 대한 설명을 들으며, 새로운 시도부분에 대해 인상이 깊었다. 데이터 속성별로 좀 더 자세히 들여다보고,
  다양한 그래프를 활용한 부분도 대단했고, 데이트 속성에서 년월일로 변경한 것 외에 년, 월, 일로 범주형 데이터를 만들어
  월별로 아파트값의 변화가 있다는 점을 찾는 등 다양한 시도를 통해 좋은 인사이트를 수영님이 많이 찾은 것이 정말 인상 깊었다.

# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
