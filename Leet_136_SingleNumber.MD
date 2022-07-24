# LeetCode 136 Single Number 

**題目：** 一個array 找出沒有重覆的數值

|input | output| 
|----|----|
|[2,2,1]|[1]|
|[4,3,2,3,2]|[4]|
|[5]|[5]|

**解法1(基本)**　　

思考：用兩個迴圈，計算數值出現的次數 

所需知識：for迴圈及基本常識
```C
int singleNum( *int nums ,int arraySize){
int i ,j ,counts,result ;
    for(i=0;i<arraySize;i++){
        counts=0;
        for(j=0;j<arraySize>;j++){
            if(nums[i]==nums[j])
                counts++;
        }
        if(counts>1)
            restult=nums[i];
    }
return restult;
}

```

**解法2(進階)**

思考：有沒有方法可以用一個迴圈解決這個問題？？

所需知識：位為運算（XOR）




 　