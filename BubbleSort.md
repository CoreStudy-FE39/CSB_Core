2022.06.26(Sun)

## ☑️ BubbleSort(버블 정렬) 🫧

> : 서로 인접한 두 원소를 검사하여 정렬하는 알고리즘

<br/>

#### ♽ 버블정렬 동작 원리

1. 배열 2개 item을 선택하고, 비교.
2. 왼쪽이 오른쪽보다 크면 swap(바꿔) (Left > Right)
3. 오른쪽으로 이동해서 해당 프로세스 반복!
4. 첫번째 cycle이 끝난 후, 다시 첨부터 cycle 반복

<br/>

#### ⏰ 버블정렬의 시간복잡도

> 배열 n-1개 item 비교

ex. item 5개라면, 4번을 비교해야 함. <br/>
🙁 최악의 경우, 모든 item swap 👉 `O(n^2)` <br/>
👉 좋은 알고리즘은 아니라 자주 사용되진 않음,, 그치만 구현이 간단해서 편리!

<br/>

📎 [노마드코더 정렬 알고리즘 Youtube 참고](https://www.youtube.com/watch?v=Bor_CRWEIXo)
