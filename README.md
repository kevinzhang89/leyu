# leyu

###首页接口
/user/home/index

in

out
coin diamond picknum


###每日任务
/achievement/task/cycle-list

in

out
每日任务的列表及相关任务的完成情况

###成就任务
/achievement/task/list

in

out
成就任务的列表及相关任务的完成情况

###悬赏任务
/bounty/task/list

in

out
悬赏任务的列表及相关任务的完成情况

###悬赏任务钻石刷新列表（每天刷新三次）
/bounty/task/refresh
in

out
产生新的悬赏任务

###悬赏任务拿金币领取任务
/bounty/task/pick
in
id 任务记录id
out
BountyTaskRecord

###悬赏任务拿钻石跳过冻结时间
/bounty/task/skip
in
id任务记录id

out
true/false

###悬赏任务　完成任务后领取奖励
/bounty/task/reward
in
id任务记录id

out
奖励内容

###奖励金兑换 暂时没有完成
/bounty/task/reward/exchange
in

out

###世界排行
/social/rank/world
in

out
list

###好友排行
/social/rank/friend
in

out
list

###奖励金列表
/account/account/list
in

out
list奖励金列表  bounty这个用户有多少奖励金

###修改昵称
/weibopay/user/nickname
in
nickname

out
Userprofile

###邮件一键删除
/message/message/all-delete
in
isSystem １　是系统邮件　０好友邮件

out
删除了几个邮件

###邮件的一键领取
/message/message/all-picked
in
isSystem １　是系统邮件　０好友邮件

out
RewardItems 领取得到的奖励

###用户的昵称头像
/weibopay/user/profile
in

out
Userprofile


###任务中红点提示是否有完成没有领取的任务
/achievement/task/notice
in

out
array
"bounty": true,
"achievement": false,
"cycle": true




