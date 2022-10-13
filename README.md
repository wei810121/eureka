# eureka
## 使用jib方法
1. 需要安裝jib檔案

## 使用docker部屬
1. 使用指令 : 
    ```
    gradle jibDockerBuild
    ```
2. 在docker指令:
   1. 執行
       ```docker
       docker run -d  -p 8900:8900 eureka:0.0.1-SNAPSHOT
       ```
   2. 查看執行
      ```
      docker ps
      ```
   3. 刪除檔案
      ```
      docker stop [image id]
      docker rm [image id]
      ```
