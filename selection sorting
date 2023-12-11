function arrSorted(arr){
  let minIndex;
  let temp;
  for( let i =0; i < arr.length;  i++){
    minIndex=i
    for (let j= i+1; j<arr.length; j++){
    if ( arr[minIndex] >arr[j]){
      minIndex=j;
    }
    
}if (minIndex!= i){
temp = arr[minIndex];
arr[minIndex] = arr[i];
arr[i] = temp;
 }
}
  return arr;
}
let arr =[ -3,5,4,7,1,-19,69,67,98,2,-3];
console.log(arrSorted(arr));