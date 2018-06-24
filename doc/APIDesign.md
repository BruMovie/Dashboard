# API文档 for BruMovie

## 用户方面

### 用户注册
post user/regist
- data
	- code
	- encryptedData
	- iv

- return
	- resultCode
	- id
	- skey

### 用户登录
post user/login
- data
	- id
	- skey

- return
	- resultCode

## 获取信息方面

### 获取影院信息
get /cinemas/get?aeraId=xxx&districtId=xxx&gps=2223488888&movieid=xxx
- return
	- resultCode
	- count
	- cinema array

### 获取电影信息
get /movie/get?cinemaid=xxx
- return
	- resultCode
	- count
	- movie array

### 获取场次信息
get / screenings/get?cinemaid=xxx&movieid=xxx&datetime=20180101
- return
	- resultCode
	- count
	- screening array

### 获取座位信息
get /seat/get?cinemaid=xxx&movieid=xxx&screeningsid=xxx
- return
	- resultCode
	- count
	- seats array

## 订单方面
### 创建订单
post /order/create
- data
	- id
	- skey
	- cinemaId
	- movieId
	- screeningId
	- seatId

- return
	- resultCode
	- orderId

### 确认订单
post /order/confirm
- data
	- id
	- skey
	- orderId

- return 
	- resultCode

### 支付订单
post /order/pay
- data
	- id
	- skey
	- orderId
	- pamentId

- return
	- resultCode

### 获取订单列表
post /order/getList
- data
	- id
	- skey
	- fromdate
	- todate

- return
	- resultCode
	- count
	- order array

### 获取订单信息
post /order/getOne
- data
	- id
	- skey
	- orderId

- return
	- resultCode
	- order data

### 取消订单
post /order/cancel
- data
	- id
	- skey
	- orderId

- return
	- resultCode