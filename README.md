# PowerBI: Analyzing the sales performance
Written by JamCourage       

**主題類別**            
Visualization (Microsoft Power BI)                      

**分析工具**      
Microsoft Power BI

**專案背景**                
此專案的數據資料來源為一跨國的運動用品製造公司，資料內容涵蓋各年度銷售主檔、客戶主檔、產品主檔等          
                
**主要目標**      
以Power BI完成以下數據分析，並制定相關改進策略：            
(一) 各銷售區域利潤分析                    
(二) 單一銷售區域利潤分析      
(三) 單一銷售區域收入分析     
(四) 各年度收入變化分析        
(五) 單一銷售區域訂單數量分析           
(六) 各年度訂單數量變化分析                                         

**步驟**            
1. 建立關聯式資料庫(data model)      
	(1) 區分lookup table與data table，以主要鍵(primary key)相連建立其關係     
	(2) data model可參考[0_DataModel.png](0_DataModel.png)                        
	
2. 各銷售區域利潤分析      
	(1) 利用矩陣、Cards、bar chart分析各區域之利潤與利潤率           
	(2) dashboard截圖與分析可參考[01_Profit_AllRegion.png](01_Profit_AllRegion.png)     
	
3. 單一銷售區域利潤分析           
	(1) 利用Slicer、matrix、Cards、bar chart分析各產品類別的利潤與利潤率     
	(2) dashboard截圖與分析可參考[02_Profit_SingleRegion.png](02_Profit_SingleRegion.png)    
	
4. 單一銷售區域收入分析            
	(1) 利用Slicer、bar chart、scatter chart分析各產品類別的營收、營收與成本間的關係             
	(2) dashboard截圖與分析可參考[03_Revenue_SingleRegion.png](03_Revenue_SingleRegion.png)   
	
5. 各年度收入變化分析           
	(1) 利用Slicer、line chart、clustered column chart分析各年度營收變化，與找出營收低點之原因             
	(2) dashboard截圖與分析可參考[04_Revenue_ByYear.png](04_Revenue_ByYear.png)     
	
6. 單一銷售區域訂單數量分析           
	(1) 利用Slicer、matrix、Cards、bar chart分析各產品類別訂單數、訂單數與利潤之關係             
	(2) dashboard截圖與分析可參考[05_Orders_SingleRegion.png](05_Orders_SingleRegion.png)     
	
7. 各年度訂單數量變化分析           
	(1) 利用Slicer、line chart、waterfall chart分析各年度訂單數變化，與找出訂單數高點之原因               
	(2) dashboard截圖與分析可參考[06_Orders_ByYear.png](06_Orders_ByYear.png)     
                 
【Power BI檔案】            
 可參考[SalesAnalysisDashboard.pbix](SalesAnalysisDashboard.pbix)               
