# IDEA:
1. 先將各個 box 的邊排序成由小到大
2. 以 step1 的 output 作為 input，對各個 box 做 sorting
3. 根據 step2 的 output，求 longest increasing subsequence，其中紀錄每一個 box 的前一個 box 為誰 
