# [反转链表](https://leetcode-cn.com/explore/interview/card/bytedance/244/linked-list-and-tree/1038/)

**头条重点**

## 题目

反转一个单链表。

```
示例:

输入: 1->2->3->4->5->NULL
输出: 5->4->3->2->1->NULL
```

## 解题思路

  1. 三个指针进行反转

```
public ListNode reverseList(ListNode head) {
    if (head == null) {
        return head;
    }

    if (head.next == null) {
        return head;
    }

    ListNode pre = head;
    ListNode cur = head.next;

    while (cur != null) {
        ListNode next = cur.next;
        cur.next = pre;

        pre = cur;
        cur = next;
    }

    head.next = null;

    return pre;
}
```
