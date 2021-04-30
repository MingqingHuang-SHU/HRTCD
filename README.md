# HRTCD
These are the data sources of Tencent Weibo in article "Information Fusion Oriented Heterogeneous Social Network for Friend Recommendation via Community Detection"

tencent-user.xls: the information about the 12,746 users
name: the unique account
fansnum: the number of followers
idolnum: the number of friends

tencent-idol-fans-*.xls: the "following" relationships among the 12,746 users
idol: the friend account
fans: the follower account

tencent-content-*.xls: the content of microblogging released by the 12,746 users
text: the content of microblogging
source_text: the initial content in interaction
source_mid: the ID of the initial microblog in interaction
type: the type of microblogging, 1--original; 2--reprint; 3--private letter; 4--reply; 5--empty reply; 6--mention; 7--comment
count: the number of times being forwarded
mcount: the number of times being commented
from1: the source type
mid: the ID of the microblog
name: the account of the user posting the microblog
