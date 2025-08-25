# iloc
import pandas as pd

# 创建一个示例 DataFrame
data = {
    '姓名': ['张三', '李四', '王五'],
    '年龄': [25, 30, 35],
    '城市': ['北京', '上海', '广州']
}
df = pd.DataFrame(data)

# 获取第一行数据
first_row = df.iloc[0]
print("第一行数据：")
print(first_row)

# 可以像访问 Series 一样获取具体列的值
print("\n第一行的姓名：", first_row['姓名'])
print("第一行的年龄：", first_row['年龄'])
