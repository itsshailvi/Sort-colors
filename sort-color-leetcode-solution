var sortColors = function(nums) {
    let hs = new Map
    let count = 0;
    for(let j = 0; j < nums.length ; j++){
        let l = nums[j]
        if(hs.has(l)){
            hs.set(l,hs.get(l)+1) 
        }
        else {
            hs.set(l,1)
        }
    }
    for(let j = 0 ; j < 3 ; j++){
        for(let k = 0 ; k < hs.get(j) ; k++){
            nums[count] = j
            count++
        }
    }
    return nums
};
