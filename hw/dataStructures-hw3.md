# Binary Search Tree Steps
### Show steps of binary search tree algorithm for the given array
---
#### **Array: [7,5,1,8,3,6,0,9,4,2]**
---
#### **Step1**
    root: 7

#### **Step2**
            root: 7
    left of 7: 5

#### **Step3**
                root: 7
        left of 7: 5
    left of 5: 1

#### **Step4**
                    root: 7
        left of 7: 5    right of 7: 8
    left of 5: 1

#### **Step5**
                    root: 7
        left of 7: 5        right of 7: 8
    left of 5: 1        left of 8: 3

#### **Step6**
                            root: 7
            left of 7: 5                right of 7: 8
    left of 5: 1    right of 5: 6   left of 8: 3

#### **Step7**
                                root: 7
                left of 7: 5                right of 7: 8
        left of 5: 1    right of 5: 6   left of 8: 3
    left of 5: 0

#### **Step8**
                                        root: 7
                    left of 7: 5                    right of 7: 8
            left of 5: 1    right of 5: 6   left of 8: 3    right of 8: 9
    left of 5: 0    

#### **Step9**
                                                    root: 7
                            left of 7: 5                                    right of 7: 8
            left of 5: 1                    right of 5: 6           left of 8: 3    right of 8: 9
    left of 5: 0    right of 1: 4     

#### **Step10**
                                                    root: 7
                            left of 7: 5                                    right of 7: 8
            left of 5: 1                    right of 5: 6           left of 8: 3        right of 8: 9
    left of 5: 0    right of 1: 4   left of 6: 2

### Time complexity: O($n$)

