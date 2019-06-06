# AI_Final_Project

* Data:https://drive.google.com/file/d/1nRqyFQkg2fGyqv3PZgc3ocmSGmXUvAAe/view
* 國內旅遊資料：34559筆
* 國外旅遊資料：49996筆
* Dataset
    * regions.pkl : pkl file, 裡面為一list包含所有region
    * tagsInsideUnique.pkl, 裡面為一list 包含所有tags(已刪除標點符號)
    * 用法： 
    ```python
    with open('tagsInsideUnique.pkl','rb') as f:
        tagsInsideUnique = pickle.load(f)
    with open('regions.pkl','rb') as f:
        regions = pickle.load(f)
    ```
* 可以使用Data_preprocess.ipynb最後Tripadvisior那邊的code將tripadvisior搜尋後的景點list抓取下來
    
      
