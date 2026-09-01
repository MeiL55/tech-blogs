---
date: 2026-08-30
tags: [greedy, sorting, binary-search, graph]
---

# Weekly Contest 415

---

## Q1. 标题 {#q1-标题}

**链接**: https://leetcode.com/problems/xxx/

### 思路
简单的 Easy 题，直接遍历数组...

### 代码
```python
class Solution:
    def solve(self, nums: List[int]) -> int:
        return sum(nums)
```

### 复杂度
- 时间: O(n)
- 空间: O(1)

---

## Q2. 标题 {#q2-标题}

**链接**: https://leetcode.com/problems/xxx/

### 思路
这道题需要排序后用双指针...

### 代码
```python
class Solution:
    def solve(self, nums: List[int]) -> List[int]:
        nums.sort()
        # 双指针逻辑...
        return result
```

### 复杂度
- 时间: O(n log n)
- 空间: O(1)

---

## Q3. 标题 {#q3-标题}

**链接**: https://leetcode.com/problems/xxx/

### 思路
这道题需要用二分搜索...

### 代码
```python
class Solution:
    def solve(self, nums: List[int], target: int) -> int:
        left, right = 0, len(nums) - 1
        while left <= right:
            mid = (left + right) // 2
            if nums[mid] == target:
                return mid
            elif nums[mid] < target:
                left = mid + 1
            else:
                right = mid - 1
        return -1
```

### 复杂度
- 时间: O(log n)
- 空间: O(1)

---

## Q4. 标题 {#q4-标题}

**链接**: https://leetcode.com/problems/xxx/

### 思路（未完成）
这道题看起来需要图论或 DP，但比赛时没做出来...

### 分析
- 卡住的原因: 没有想到正确的状态定义
- 看了题解后的理解: 应该用拓扑排序 + DP

---

## 📝 比赛复盘

### ✅ 做得好的地方
1. Q1 和 Q2 思路清晰，速度快
2. 及时放弃 Q4，集中精力做 Q3，避免浪费时间

### ❌ 需要改进
1. 二分搜索边界条件还是容易出错，需要多练
2. 对图论和 DP 的组合问题理解不足
3. 比赛时间管理：应该给 Hard 题留更多思考时间

### 🎓 学到的知识点
- 复习了二分搜索的标准写法
- 了解了拓扑排序在竞赛中的应用场景
- 发现自己在贪心算法上还有薄弱之处

---

**参考资源**: 
- [官方题解](https://leetcode.com/discuss/general-discussion/...)
- 相关知识点: 二分搜索、排序、双指针
