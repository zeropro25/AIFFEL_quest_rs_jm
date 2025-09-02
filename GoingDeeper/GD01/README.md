# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 임정민
- 리뷰어 : 장수봉


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    <img width="985" height="891" alt="image" src="https://github.com/user-attachments/assets/bbc81c50-ace1-41dd-a451-688d673656ed" />

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    <img width="899" height="383" alt="image" src="https://github.com/user-attachments/assets/8b405ca1-5a95-4cd3-8e42-5d5dbf869e5c" />
    <img width="898" height="257" alt="image" src="https://github.com/user-attachments/assets/5bf45a40-7b57-40b7-9f15-118a96a92402" />


        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인 - 
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          
    - 전처리 후 다시 실험
    <img width="1001" height="686" alt="image" src="https://github.com/user-attachments/assets/9021048d-709f-4f8c-bcb1-7709d76b9104" />

    - 모델과 vocab size 변경하면서 비교 실험
    <img width="934" height="896" alt="image" src="https://github.com/user-attachments/assets/ce3a839d-f487-4b18-9f07-5a3db2efa165" />
    <img width="777" height="297" alt="image" src="https://github.com/user-attachments/assets/a4311717-fbe3-4ad5-ba48-c2dae84246b4" />


        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    <img width="836" height="524" alt="image" src="https://github.com/user-attachments/assets/9aa16f33-bafc-4bbf-bd49-f9029832157a" />

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    <img width="634" height="316" alt="image" src="https://github.com/user-attachments/assets/e0d68eba-0267-48ef-a34b-24fb4bb4db61" />



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- 여러 조건을 변경하면서 비교 실험 한 것이 좋았습니다
<img width="362" height="168" alt="image" src="https://github.com/user-attachments/assets/26b7e8c7-1784-46fd-ae1a-90062b3fb5c3" />

- 비교 실험이 끝난 후에도 전처리를 다시하는 시도를 하였는데 시간이 충분하였으면 성능을 높일 수 있었다고 보여집니다
