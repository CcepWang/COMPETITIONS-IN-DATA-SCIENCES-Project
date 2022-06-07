# COMPETITIONS-IN-DATA-SCIENCES-Project

### 資料處理
- 資料清洗
- 34個特徵提取
- ![image](https://user-images.githubusercontent.com/37070545/172198774-62faa82a-8857-49c9-b972-2bcd4d8277f7.png)
### 資料儲存
- 處理完的資料會儲存成df_work.pkl
- 第二次執行後都可以直接讀取這個檔案後就可以往下訓練model
### 訓練
- 使用了兩個模型
- LightGBM
- ![lightbgm](https://user-images.githubusercontent.com/37070545/172199115-90c4d8f3-b013-4ca4-9683-9e1a50a06a10.png)
- XGBoost
- ![xgb](https://user-images.githubusercontent.com/37070545/172199141-7415f8c2-0f4d-4ec1-9da6-f240bfda820f.png)
### Ensemble
- 使用多次的結果以及不同參數得到的模型
- 將結果去做加權平均
### 結果
![image](https://user-images.githubusercontent.com/37070545/172199308-0d56955f-9fab-4108-a950-40979ca78ea2.png)
![image](https://user-images.githubusercontent.com/37070545/172283359-f9c054b9-6e44-40bd-9fae-8b7172e78513.png)
