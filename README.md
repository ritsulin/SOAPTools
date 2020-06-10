# PoC of JBoss JMXInvokerServlet Deserialize

## Test Envirment(JBOSS AS 4.0.5)

* Start envirment by docker

```
docker-compose up -d
```

## DeserializeExploit.jar
### Supported
1. JBOSS 
2. WebLogic 
3. WebSphere 


### Basic using step

1. Select Target's SOAP type (JBOSS, WebLogic, WebSphere)
2. Paste the target URL in **目標**
3. Click the **獲取信息** button.
4. If it's successful, the frame will show the information of target.

### Other function

#### Command
1. Select the **執行命令**.
2. Type the command in the command bar(**在此輸入執行命令**).
3. Click the **執行** button.
4. The result of command will show in the frame.

#### WebShell Upload
1. Select the **webshell上傳**.
2. Type the upload path in the bar(**在此輸入文件上傳的路徑**).
>For example: https://xx.xx.xx/shell
3. Click the **執行** button.
4. The result of command will show in the frame.
5. Click the **確定** button, result of the uploaded file will show in the bottom bar(**此處顯示文件上傳結果訊息**)

PS. You can use manual shell code and just type it the middle frame.

#### List Files of the Target
1. Select the **文件管理**.
2. **當前目錄** shows the current path.
3. Click the **列目錄** button will list the files of the path.
4. Click the **清空** button will clear the list.



### JavaDeserH2HC
#### Please reference the README.md in JavaDeserH2HC folder