

获取俱乐部成员
url: /v1/teams/members.json
method: GET
参数:
team_id: 俱乐部ID
返回：
{
  "code": 0,
  "data": [{
            "id":137,
            "email":"",
            "mobile":"15195010350",
            "password_digest":"$2a$10$5aKms0u9CjoJNMMPbD5R3Ol98.DgJ0MsdUD3cZ0yUXFGNe13sXrZm",
            "created_at":"2015-05-15 01:40:32",
            "updated_at":"2015-06-01 09:23:57",
            "sid":"7678cbeda167f27ec5d8c137027dadf3",
            "nickname":"15195010350",
            "age":"",
            "sex":0,
            "following_count":4,
            "followed_count":2,
            "birthday":"",
            "is_privated":"",
            "addr":"",
            "unionid":"",
            "avatar_url":"http://cospo.oss-cn-qingdao.aliyuncs.com/attachments/6b/d283826d8020018cbb4c4af4e210f6.png",
            "last_check_code":"",
            "lng":"119.960065",
            "lat":"31.790095",
            "uuid":"97568124",
            "last_activated_at":"",
            "like_project_ids":"1,2",
            "rank":0,
            "distance":153173.14,
            "role":"leader"
        }]
}


用户参与的俱乐部
url: /v1/users/teams.json
jsonParam:{
    page = 1;
    per = 10;
    sid = 05b940f5c0bbba4d8d01ec9c5449ead9;
    uid = 142;
    "user_id" = 142;
    "user_lat" = "31.218439";
    "user_lng" = "121.430019";
}


俱乐部日志
url: /v1/teams/feeds.json
jsonParam:{
    page = 1;
    per = 10;
    sid = 05b940f5c0bbba4d8d01ec9c5449ead9;
    "team_id" = 308;
    uid = 142;
}
