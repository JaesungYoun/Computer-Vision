# Computer-Vision

# 1. Edge-Detector 구현

이미지 로드 및 저장 기능 외에는 OpenCV 라이브러리를 사용하지 않고 직접 Edge-Detector를 구현

5가지 방법 사용

<img width="222" alt="original_image" src="https://user-images.githubusercontent.com/73388615/148053655-57c71f03-bb89-4fd6-82e4-f871bf677ee0.PNG">                                  ![image](https://user-images.githubusercontent.com/73388615/148053911-115c43bf-8f34-40da-9293-b7fc2529d3d2.png)





## 1) Gradient    

![image](https://user-images.githubusercontent.com/73388615/148052770-a8ff5530-0a5f-4046-9a6b-f33a78929549.png)                             

![image](https://user-images.githubusercontent.com/73388615/148052796-cf1c6945-9862-41cf-b3c3-67b98da6d75f.png)




## 2) Derivative of Box Filter       

![image](https://user-images.githubusercontent.com/73388615/148052931-c0f237ac-1e2a-49e7-83a6-48efd880a2eb.png)




## 3) Derivative of Gaussian(DoG)           
        
               
                   

![image](https://user-images.githubusercontent.com/73388615/148052999-2635b182-b6e0-46d6-80c2-e7d6b842afe7.png)

![image](https://user-images.githubusercontent.com/73388615/148053028-9fa6af12-6b7c-408f-8a3e-fd0c8659a9bc.png)

![image](https://user-images.githubusercontent.com/73388615/148053554-9399942b-2cf6-49d3-b921-62004eb706df.png)



## 4) Differnce of Gaussian(DoG)     


![image](https://user-images.githubusercontent.com/73388615/148053126-7a767ccc-673f-4790-9a03-2400bc03bd32.png)


## 5) Laplacian of Gaussian(LoG)

![image](https://user-images.githubusercontent.com/73388615/148053172-dff7bc8b-77f9-4f19-80cf-ecd620230a5c.png)

![image](https://user-images.githubusercontent.com/73388615/148053221-18fac25d-8d8f-49e8-9ba7-d933afef3535.png)




