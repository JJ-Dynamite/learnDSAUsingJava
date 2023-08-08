# Basic Sorting Alog 
- Bubble Sort

```js
public static void bubbleSortDescending(int arr[]){
  for( int turn=0 ; turn< arr.length-1 ; turn++){
    for (int j=0 ; j<arr.length-1-turn ; j++){
        if(arr[j]<arr[j+1]){
          int temp = arr[j]
          arr[j] =arr[j+1]
          arr[j+1]= temp
          }
    }
}
}
```
- Selection Sort
  
```js
public static void selectionSortDescending(int arr[]){
      for (int turn=0 ; turn<arr.length ; turn++){
          int minPos = turn;
          for(int j= turn+1 ;j<arr.length ; j++){
              if(arr[minPos]<arr[j]){
                  minPos=j;
                }
          }

          int temp = arr[turn];
          arr[turn]=arr[minPos];
          arr[minPos]=temp;
      }
}
```
