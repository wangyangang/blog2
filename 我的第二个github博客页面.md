- 插入代码测试
```cs
 private void InitizeEvaluationEnvironment()
        {
            DataTable dt = CreateTargetTable();

            Utility.ConvertEntityToTable(_currentEvaluationEnvironmentInfo, dt);
            SetDataGridStyleForData(dataGrid);
            dataGrid.DataSource = dt;
        }
```
- 插入图片测试

![default](https://user-images.githubusercontent.com/16028271/28612196-0dfc48a4-7221-11e7-863b-01c89929ae40.jpg)
