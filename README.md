# practise

1、 输出从1到100之间所有的整数;

2、 输出从1到100之间所有的奇数;

3、 输出从1到100之间所有不能被3整除的数;并输出这些整数的和

1、
```
public class Homework{
	public static void main(String[] args){
		for(int i=1;i<=100;i++){
			System.out.println(i);
	}
}
}
```

2、
```
public class Homework{
	public static void main(String[] args){
		for(int i=1;i<=100;i+=2){
			System.out.println(i);
	}
}
}
```

3、
```
public class Homework{
	public static void main(String[] args){
		for(int i=1;i<=100;i++){
			if(i%3!=0){
				System.out.println(i);
			}
			
	}
}
}
```
