- ð Hi, Iâm @Kapok-chen
- ð Iâm interested in ...
- ð± Iâm currently learning ...
- ðï¸ Iâm looking to collaborate on ...
- ð« How to reach me ...

<!---
Kapok-chen/Kapok-chen is a â¨ special â¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

### ä¸ãæ°æ®ç»æä¸ç®æ³æ¦è¿°

<hr/>

#### 1.1 ðä»ä¹æ¯æ°æ®ç»æ

```
æç§è®¡ç®æºçå­å¨ï¼å°æ°æ®åç´ ç¨ä¸å®å³ç³»è¡¨ç¤ºçéå
```

#### 1.2 ð«ç»æçåç±»

çº¿æ§ç»æï¼

```
å­å¨ä¸å¯¹ä¸çå³ç³»ï¼çº¿æ§ç»æçå­å¨æ¹å¼åä¸ºé¡ºåºå­å¨ï¼é¡ºåºè¡¨ãæ°ç»ãéåãæ ãï¼åé¾å¼å­å¨ï¼é¾è¡¨ãå­å¨åç´ å°åå¯ä»¥è¿ç»­ä¹å¯ä»¥ä¸è¿ç»­ãï¼

é¡ºåºå­å¨åé¾å¼å­å¨çä¸»è¦åºå«ï¼å°±æ¯å°åè¿ç»­ä¸ä¸è¿ç»­
```

éçº¿æ§ç»æ

```
äºä½æ°ç»ãå¤ä¸ºæ°ç»ãå¹¿ä¹è¡¨ãæ ãå¾
```



#### 1.3 ðæ°ç»

##### ç¨çæ°ç»

> å¼ä¾ï¼ä¸ä¸ªæ£çï¼å¦ä½è®°è½½é»ç½ä¸¤å­çä½ç½®ï¼
>
> ææ³å°çæ¯äºç»´æ°ç»ï¼ä½æ¯äºç»´æ°ç»çé»è®¤å¼æ¯0ï¼å°±æµªè´¹äºè®¸å¤çå­å¨ç©ºé´

æ­¤æ¶ï¼å¯ä»¥éç¨ç¨çæ°ç»

> æè·¯ï¼ç¨ä¸ä¸ªæ°ç»åªè®°å½å è¡å åï¼æå¤å°ä¸ªä¸åçå¼ï¼æä¸åçå¼ä»¥åè¡åè®°å½å¨ä¸ä¸ªå°è§æ¨¡çæ°ç»ä¸­ï¼ä»èè¾¾å°åç¼©æ°ç»çç®ç

> åå§æ°ç»

![1672410674508](E:\å­¦ä¹ \ä¸ä¸å­¦ä¹ \æ°æ®ç»æ\pic\1672410674508.png)

> ä¸æ ä¸º0ç åªè®°å½äºæ»è¡ãæ»åï¼å±è®¡å¤å°ä¸ªä¸ååç´ 
>
> å©ä¸çä¸æ ï¼è®°å½äºå·ä½çè¡åï¼åå·ä½çåç´ 

![1672410285791](E:\å­¦ä¹ \ä¸ä¸å­¦ä¹ \æ°æ®ç»æ\pic\1672410285791.png)

> ç¨çæ°ç»çåºç¨åºæ¯ï¼äºå­æ£ï¼å°å¾
>
> äºç»´æ°ç»==>è½¬ç¨çæ°ç»
>
> 1.éåæ´ä¸ªäºç»´æ°ç»ï¼å¾å°æ»ææä¸ªæ° sum
>
> 2.æ ¹æ®sum åå»ºç¨çæ°ç» sparseArr int [sum+1][3]
>
> 3.å°äºç»´æ°ç»çææå¼ï¼å­å¥å°ç¨çæ°ç»ä¸­

ä»£ç å®ç°

åææ£çåå»ºåºæ¥

```java
        // åå»ºä¸ä¸ªåå§çäºç»´æ°ç» 11*11
        //0è¡¨ç¤ºæ å­ï¼1ä¸ºé»å­ï¼2ä¸ºç½å­
        int chessArra[][] = new int[11][11];
        //ç¬¬ä¸è¡ï¼ç¬¬äºåä¸ºé»å­
        chessArra[1][2] = 1;
        //ç¬¬äºè¡ï¼ç¬¬ä¸åä¸ºç½å­
        chessArra[2][3] = 2;
        //è¾åºæ°ç»
        for (int[] row:chessArra){
            for (int data:row){
                System.out.printf("%d\t", data);
            }
            System.out.println();
        }
```

```java
0	0	0	0	0	0	0	0	0	0	0	
0	0	1	0	0	0	0	0	0	0	0	
0	0	0	2	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
```



```java
        // åå»ºä¸ä¸ªåå§çäºç»´æ°ç» 11*11
        //0è¡¨ç¤ºæ å­ï¼1ä¸ºé»å­ï¼2ä¸ºç½å­
        int chessArra[][] = new int[11][11];
        //ç¬¬ä¸è¡ï¼ç¬¬äºåä¸ºé»å­
        chessArra[1][2] = 1;
        //ç¬¬äºè¡ï¼ç¬¬ä¸åä¸ºç½å­
        chessArra[2][3] = 2;
        //è¾åºæ°ç»
        for (int[] row:chessArra){
            for (int data:row){
                System.out.printf("%d\t", data);
            }
            System.out.println();
        }

        //å°äºç»´æ°ç» ===ã ç¨çæ°ç»ï¼éåäºç»´æ°ç»ï¼å¾å°é0çä¸ªæ°
        int sum = 0;
        for (int i = 0; i < chessArra.length; i++) {
            for (int j = 0; j < chessArra.length; j++) {
                if (chessArra[i][j] !=0){
                    sum++;
                }
            }
        }
        // æå°é0ä¸ªæ°
        System.out.println(sum);

        //åå»ºç¨çæ°ç»
        int sparseArr[][] = new int[sum+1][3];
        //ç»ç¨çæ°ç»èµå¼
        sparseArr[0][0] = 11;
        sparseArr[0][1] = 11;
        sparseArr[0][2] = sum;

        //å°äºç»´æ°ç»é0å¼ï¼å­æ¾å°ç¨çæ°ç»ä¸­
        //count ç¨äºè®°å½æ¯ç¬¬å ä¸ªé0çæ°æ®
        int count = 0;
        for (int i = 0; i < chessArra.length; i++) {
            for (int j = 0; j < chessArra.length; j++) {
                if (chessArra[i][j] !=0){
                    //é0æ°æ®
//                    sparseArr[?][0] = i;
//                    sparseArr[?][1] = j;
//                    sparseArr[?][2] = chessArra[i][j]
                    count++;
                    sparseArr[count][0] = i;
                    sparseArr[count][1] = j;
                    sparseArr[count][2] = chessArra[i][j];
                }
            }
        }


        for (int[] row:sparseArr){
            for (int data:row){
                System.out.printf("%d\t", data);
            }
            System.out.println();
        }
    }
```

```java
0	0	0	0	0	0	0	0	0	0	0	
0	0	1	0	0	0	0	0	0	0	0	
0	0	0	2	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	

11	11	2	
1	2	1	
2	3	2	
```



è¿åäºç»´æ°ç»

```java
        // åå»ºä¸ä¸ªåå§çäºç»´æ°ç» 11*11
        //0è¡¨ç¤ºæ å­ï¼1ä¸ºé»å­ï¼2ä¸ºç½å­
        int chessArra[][] = new int[11][11];
        //ç¬¬ä¸è¡ï¼ç¬¬äºåä¸ºé»å­
        chessArra[1][2] = 1;
        //ç¬¬äºè¡ï¼ç¬¬ä¸åä¸ºç½å­
        chessArra[2][3] = 2;
        //è¾åºæ°ç»
        for (int[] row:chessArra){
            for (int data:row){
                System.out.printf("%d\t", data);
            }
            System.out.println();
        }

        //å°äºç»´æ°ç» ===ã ç¨çæ°ç»ï¼éåäºç»´æ°ç»ï¼å¾å°é0çä¸ªæ°
        int sum = 0;
        for (int i = 0; i < chessArra.length; i++) {
            for (int j = 0; j < chessArra.length; j++) {
                if (chessArra[i][j] !=0){
                    sum++;
                }
            }
        }
        // æå°é0ä¸ªæ°
        System.out.println(sum);

        //åå»ºç¨çæ°ç»
        int sparseArr[][] = new int[sum+1][3];
        //ç»ç¨çæ°ç»èµå¼
        sparseArr[0][0] = 11;
        sparseArr[0][1] = 11;
        sparseArr[0][2] = sum;

        //å°äºç»´æ°ç»é0å¼ï¼å­æ¾å°ç¨çæ°ç»ä¸­
        //count ç¨äºè®°å½æ¯ç¬¬å ä¸ªé0çæ°æ®
        int count = 0;
        for (int i = 0; i < chessArra.length; i++) {
            for (int j = 0; j < chessArra.length; j++) {
                if (chessArra[i][j] !=0){
                    //é0æ°æ®
//                    sparseArr[?][0] = i;
//                    sparseArr[?][1] = j;
//                    sparseArr[?][2] = chessArra[i][j]
                    count++;
                    sparseArr[count][0] = i;
                    sparseArr[count][1] = j;
                    sparseArr[count][2] = chessArra[i][j];
                }
            }
        }


        for (int[] row:sparseArr){
            for (int data:row){
                System.out.printf("%d\t", data);
            }
            System.out.println();
        }

        //å°ç¨çæ°ç»è¿åä¸ºäºç»´æ°ç»
        //1.åè¯»åç¨çæ°ç»
        int chessArr2[][] = new int[sparseArr[0][0]][sparseArr[0][1]];

        //è¯»åç¨çæ°ç» éæ°èµå¼ç» äºç»´æ°ç»
        for (int i = 1; i < sparseArr.length; i++) {
            chessArr2[sparseArr[i][0]][sparseArr[i][1]] = sparseArr[i][2];
        }

        for (int[] row:chessArr2){
            for (int data:row){
                System.out.printf("%d\t", data);
            }
            System.out.println();
        }
```

```java
0	0	0	0	0	0	0	0	0	0	0	
0	0	1	0	0	0	0	0	0	0	0	
0	0	0	2	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
2
11	11	2	
1	2	1	
2	3	2	
0	0	0	0	0	0	0	0	0	0	0	
0	0	1	0	0	0	0	0	0	0	0	
0	0	0	2	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
0	0	0	0	0	0	0	0	0	0	0	
```



##### éå

> éåçç¹ç¹æ¯åè¿ååºï¼å¯ä»¥ç¨**æ°ç»åé¾è¡¨å®ç°**
>
> > éåæéå¤´ãfrontã,éå°¾ãrearã,åºéæ¯ front ï¼å¥éæ¯å¨rear
>
> å®ç°æè·¯ï¼å½å¥éæ¶ï¼rear+1ï¼éç©ºæ¶éè¦å¤æ­ front == rearï¼æ¯æ¬¡å¥éæ¶é½éè¦å¤æ­æ¯å¦éæ»¡
>
> â				éæ»¡ï¼éè¦ rear == maxSize-1
>
> ä½¿ç¨åºæ¯ï¼é¶è¡çå«å·ç³»ç»

```java
// ç¨æ°ç»æ¨¡æéåï¼ç¼åArrayQueueç±»
class ArrayQueue{
    private int maxSize;//è¡¨ç¤ºå½åéåçæå¤§å®¹é
    private int front;//éå¤´
    private int rear;//éå°¾
    private int[] arr;//è¯¥æ°ç»ç¨äºæ¨¡æéåï¼å­æ¾æ°æ®

    //åå»ºéåçæé å¨
    public ArrayQueue(int arrMaxSize){
        maxSize = arrMaxSize;
        arr = new int[maxSize];

        //åå§åéåæ¶ï¼frontæåéåå¤´é¨åä¸ä¸ªä½ç½®ãrearæåéå°¾çæåä¸ä¸ªæ°æ®
        front = rear = -1;
    }

    //å¤æ­éæ¯å¦æ»¡
    private boolean isFull(){
        return rear == maxSize - 1;
    }

    //å¤æ­éç©º
    private boolean isQueueEmpty(){
        return rear == front;
    }

    //å¥é
    public void addQueue(int n){
        //å¤æ­éæ»¡
        if (isFull()){
            System.out.println("éæ»¡");
            return;
        }

        //è®©rearçä¸æ ååç§»ï¼å°±å®ç°éå°¾çæéååç§»äº
        rear++;
        arr[rear] = n;
    }

    //åºé
    public <T> Object outQueue(){
        //åºéå¤æ­éç©º
        if (isQueueEmpty()){
            //ä¸ºç©ºæåºå¼å¸¸
            return new RuntimeException("éåä¸ºç©º");
        }
        front++;//åºéæ¯å¨éå¤´
        System.out.println("åºéåç´ ä¸ºï¼"+arr[front]);
        return arr[front];
    }

    //è·åéåä¸­çæææ°æ®
    public void getQueue(){
        for (int i = 0; i < arr.length; i++) {
            System.out.println(arr[i]);
        }
    }
}
```



```java
    public static void main(String[] args) {
        ArrayQueue arrayQueue = new ArrayQueue(3);
        arrayQueue.addQueue(1);
        arrayQueue.addQueue(2);
        arrayQueue.addQueue(3);
        arrayQueue.getQueue();
        //åºé
        arrayQueue.outQueue();
        arrayQueue.outQueue();
        arrayQueue.outQueue();
    }
```

```java
1
2
3
åºéåç´ ä¸ºï¼1
åºéåç´ ä¸ºï¼2
åºéåç´ ä¸ºï¼3
```



##### å¾ªç¯éå

> è®© front æåéåçç¬¬ä¸ä¸ªåç´ ï¼ä¹å°±æ¯æ°ç»çç¬¬ä¸ä¸ªåç´  from = 0
>
> è®© rear æåéåçæåä¸ä¸ªåç´ çåä¸ä¸ªä½ç½®ãrear = 0ãï¼å¸æç©ºåºä¸ä¸ªç©ºé´ï¼è¿ä¸ªç©ºé´å°±æ¯ä¸ºäºå¤æ­éåæ¯å¦æ»¡äºï¼å¨å¥éæ¶çæ¯å¦è¿æç©ºé´å¯ä»¥ãå¨å¯¹ éå®¹éåæ¨¡
>
> æ­¤æ¶çéæ»¡æ¡ä»¶ä¸º ï¼rear+1ï¼% maxSize == front
>
> éç©ºï¼rear ==  front
>
> éåçææåç´ ä¸ªæ°ä¸ºï¼ï¼rear + maxSize - frontï¼% maxSize



```java
//æ¨¡æå¾ªç¯éå
class CircleQueue{
    private int maxSize;//è¡¨ç¤ºéåçæå¤§å®¹é
    private int front;//éå¤´
    private int rear;//éå°¾
    private int[] arr;//æ°ç»æ¨¡æå¾ªç¯éå

    //åå§åéå
    public CircleQueue(int arrMaxSize){
        maxSize = arrMaxSize;
        arr = new int[maxSize];
        //åå§æ¢éå¤´ï¼éå°¾åç´ 
        front = 0;
        rear = 0;
    }

    //å¤æ­éæ»¡
    public boolean isFull(){
        return (rear + 1) % maxSize == front;
    }

    //å¤æ­éç©º
    public boolean isQueueEmpty(){
        return front == rear;
    }

    //å¥é
    public void addQueue(int n){
        //å¤æ­éæ»¡
        if (isFull()){
            return;
        }
        //éåæ²¡ææ»¡å°±å¥é,å ä¸ºéå°¾æ¬èº«å°±æåæ°ç»çç¬¬ä¸ä¸ªåç´ ï¼æä»¥ä¸éè¦++æä½
        arr[rear] = n;
        // å°æéååç§»
        rear = (rear + 1) % maxSize;
    }

    //åºé
    public <T> Object outQueue(){
        //å¤æ­éåæ¯å¦ä¸ºç©º
        if (isQueueEmpty()) {
            return new RuntimeException("éæ»¡");
        }
        //åºéå¨éå¤´åºï¼å ä¸ºéå¤´æéæåçä¹æ¯æ°ç»çç¬¬ä¸åç´ ï¼åå°éå¤´åç´ ä¿å­å°ä¸ä¸ªä¸´æ¶åéä¸­ï¼åå°éå¤´æéåç§»
        int temp = arr[front];
        front = (front + 1) % maxSize;
        System.out.println("åºé"+temp);
        return temp;
    }

    //æå°éå
    public void getQueue(){
        // éåéåä¸­çææåç´ 
        int effectiveEle = (rear + maxSize - front) % maxSize;
        for (int i = front; i < front+effectiveEle; i++) {
            System.out.println(arr[i]);
        }
    }
}
```



æ­¤æ¶çæææ°æ®ä¸º2ï¼å ä¸ºé¢çä¸ä¸ªç©ºé´ä½ç½®

```java
    public static void main(String[] args) {
        CircleQueue circleQueue = new CircleQueue(4);
        circleQueue.addQueue(1);
        circleQueue.addQueue(2);
        circleQueue.addQueue(3);
        circleQueue.getQueue();

        circleQueue.outQueue();
        circleQueue.addQueue(4);
        circleQueue.getQueue();

    }
```

```
1
2
3
åºé1
2
3
4
```



#### 1.4 ðé¾è¡¨

> åä¸ºæ¯å¦å¸¦ å¤´èç¹
>
> > é¾è¡¨å¸¦æå¤´èç¹çæä¸ä¸ªé¨åç»æï¼å¤´èç¹ãå­æ¾çæ¯å°åããdataåãnextåãå­æ¾ä¸ä¸ä¸ªåç´ å°åã
> >
> > ä¸å¸¦å¤´èç¹çæä¸¤ä¸ªé¨åç»æï¼dataåãnextå
>
> > å¤´èç¹ä¸å­æ¾æ°æ®

ç©çç»æãä¹æ¯å¨åå­ä¸­çå®éå­å¨ç»æä¸è¿ç»­ã                               é»è¾ç»æãè¿ç»­ã

![1672624723190](E:\å­¦ä¹ \ä¸ä¸å­¦ä¹ \æ°æ®ç»æ\pic\1672624723190.png)![image-20230102100726967](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20230102100726967.png)

```java
//èç¹å¯¹è±¡ï¼æ¯ä¸ä¸ªHeroNodeé½æ¯ä¸ä¸ªèç¹å¯¹è±¡
class HeroNode{
    public int hno;//ç¼å·
    public String name;//åå­
    public String nickeName;//æµç§°
    public HeroNode next;//ä¸ä¸ä¸ªèç¹

    //æé å¨
    public HeroNode(int hno,String name,String nickeName){
        this.hno = hno;
        this.name = name;
        this.nickeName=nickeName;
    }

    //æå°
    @Override
    public String toString() {
        return "HeroNode{" +
                "hno=" + hno +
                ", name='" + name + '\'' +
                ", nickeName='" + nickeName + '\'' +
                '}';
    }
}

//å®ä¹ä¸ä¸ª SingleLikedList æ¥ç®¡çè±é
class SingleLikedList{
    //1.åå§åä¸ä¸ªå¤´èç¹,åªæ¯ä»£è¡¨å¤´èç¹ï¼ä¸å­æ¾ä»»ä½æ°æ®
    private HeroNode headNode = new HeroNode(0,"","");

    //æ·»å èç¹å°ååé¾è¡¨
    //å®ç°æè·¯ï¼å½ä¸èèå½åé¾è¡¨ç¼å·çé¡ºåºæ¶
    //1. æ¾å°å½åé¾è¡¨çæåä¸ä¸ªèç¹
    //2. å°æåè¿ä¸ªèç¹ç next æåæ°çèç¹
    public void addNode(HeroNode node){
        // headNode ä¸è½æï¼æä»¥éè¦ä¸ä¸ªä¸´æ¶åéï¼ä¿æå¤´èç¹ä¸è½å¨
        HeroNode temp = headNode;

        //éåæ¾å°æå
        while (true){
            //æ¾å°é¾è¡¨çæåäº
            if (temp.next == null){
                break;
            }

            //å¦ææ²¡ææ¾å°æåï¼å°±å°tempå¾åç§»
            temp = temp.next;
        }

        //å½éåºwhileå¾ªç¯æ¶ï¼æ­¤æ¶çtempå°±æåäºé¾è¡¨çæå, è®©tempæåä¸ä¸ä¸ªèç¹
        temp.next = node;
    }

    //æ¾ç¤ºé¾è¡¨ãéåã
    public void showInfo(){
        //åå¤æ­é¾è¡¨æ¯å¦ä¸ºç©º
        if (headNode.next == null){
            System.out.println("é¾è¡¨ä¸ºç©º");
            return;
        }

        //éåé¾è¡¨æ¶ï¼éè¦ä¸åçæåä¸ä¸ä¸ªèç¹ï¼å¤´èç¹åä¸è½å¨
        HeroNode temp = headNode.next;
        while (true){
            //åå¤æ­æ¯å¦å°é¾è¡¨æå
            if(temp == null){
                break;
            }
            //å¦æä¸ä¸ºç©ºï¼å°±æå°èç¹ä¿¡æ¯
            System.out.println(temp);
            //tempåç§»ï¼æ¾å°ä¸ä¸ä¸ªèç¹
            temp = temp.next;
        }
    }
}
```

```java
    public static void main(String[] args) {
        HeroNode heroNode1 = new HeroNode(1,"å®æ±","åæ¶é¨");
        HeroNode heroNode2 = new HeroNode(2,"å¢ä¿ä¹","çéºéº");
        HeroNode heroNode3 = new HeroNode(3,"å´ç¨","æºå¤æ");
        HeroNode heroNode4 = new HeroNode(4,"æå²","è±¹å­å¤´");

        SingleLikedList singleLikedList = new SingleLikedList();
        singleLikedList.addNode(heroNode1);
        singleLikedList.addNode(heroNode4);
        singleLikedList.addNode(heroNode3);
        singleLikedList.addNode(heroNode2);

        singleLikedList.showInfo();
    }
```

```java
HeroNode{hno=1, name='å®æ±', nickeName='åæ¶é¨'}
HeroNode{hno=4, name='æå²', nickeName='è±¹å­å¤´'}
HeroNode{hno=3, name='å´ç¨', nickeName='æºå¤æ'}
HeroNode{hno=2, name='å¢ä¿ä¹', nickeName='çéºéº'}
```

