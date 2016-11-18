 <!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>要求四：制作独立功能模块</title>
    <link rel="stylesheet" href="quoteCss/bootstrap.min.css">
    <link rel="stylesheet" href="quoteJs/layui/css/layui.css">
    <link rel="stylesheet" href="quoteCss/common.css">
    <link rel="stylesheet" href="css/requirement4.css">
    <script src="quoteJs/jquery-1.11.1.js" type="text/javascript"></script>
</head>
<body>
    <div class="container">
        <div class="navbar navbar-default row" role="navigation">
          　<div class="navbar-header">
          　    <a href="javascript:void(0);;" class="navbar-brand">个人中心</a>
          　</div>
            <ul class="nav navbar-nav pull-right">
                <li><a href="javascript:void(0);;" class="item" id="enter">登陆</a></li>
                <li class="shu-xian"><a href="javascript:void(0);;">|</a></li>
                <li><a href="javascript:void(0);;" class="item" id="login">注册</a></li>
            </ul>
        </div>
        <div class="content row">
            <div class="col-md-3 user-img">
                <p class="h4">用户靓照</p>
                <img src="img/a1.jpg" alt="用户图片">
            </div>
            <div class="col-md-9 user-info">
                <p class="h4">个人信息</p>
                <div class="row info-box">
                    <div class="col-md-6">
                        姓&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;名：<span id="user_name">王小二</span>
                    </div>
                    <div class="col-md-6">
                        性&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;别：<span id="user-sex">男</span>
                    </div>
                    <div class="col-md-6">
                        籍&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;贯：<span>海南岛</span>
                    </div>
                    <div class="col-md-6">
                        名&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;族：<span>藏族</span>
                    </div>
                    <div class="col-md-6">
                        最高学历：<span>五本</span>
                    </div>
                    <div class="col-md-6">
                        毕业学校：<span>拉登幼儿园</span>
                    </div>
                    <div class="col-md-6">
                        所学专业：<span id="ddd">弹珠珠</span>
                    </div>
                    <div class="col-md-6">
                        就业公司：<span>海南岛保卫队</span>
                    </div>
                    <div class="col-md-6">
                        职&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;位：<span>大队长</span>
                    </div>
                    <div class="col-md-12 change-info">
                        <a href="javascript:void(0);" class="btn btn-primary" id="changeInfo">修改用户信息</a>
                    </div>
                </div> 
            </div>
        </div>
        <p class="h4">职业生涯</p>
        <div class="row career-thumbnail">
            <div class="col-md-3 col-xs-6">
                <a href="javascript:void(0);;" class="thumbnail">
                    <img src="img/a1.jpg" alt="">
                </a>
                <div class="caption">
                    <h4 class="h4">亚什兰（中国）投资有限公司</h4>
                    <p>亚什兰（中国）投资有限公司是一家世界500强的上市公司，在职期间主要任职现场水处理服务工程师一职。参与过四川达州普光气田循环水场第二套循环水系统...</p>
                    <p>
                        <a href="##" class="btn btn-primary">点击查看</a>
                    </p>
                </div>
            </div>
            <div class="col-md-3 col-xs-6">
                <a href="javascript:void(0);;" class="thumbnail">
                    <img src="img/a2.jpg" alt="">
                </a>
                <div class="caption">
                    <h4 class="h4">索理思（上海）化工有限公司</h4>
                    <p>索理思（上海）化工有限公司是一件专业生产工业水处理药剂外资企业，公司有健全的销售系统，和专业的服务团队。在职期间负责过APP纸厂的两套循环水系统...</p>
                    <p>
                        <a href="##" class="btn btn-primary">点击查看</a>
                    </p>
                </div>
            </div>
            <div class="col-md-3 col-xs-6">
                <a href="javascript:void(0);;" class="thumbnail">
                    <img src="img/a3.jpg" alt="">
                </a>
                <div class="caption">
                    <h4 class="h4">巴克曼（上海）化工有限公司</h4>
                    <p>巴克曼（上海）实验室化工有限公司是一家专业生产水处理药剂的外资企业，进入国内较早，目前占在中国1%的市场。在职期间参与过四川石化循环水两套系统...</p>
                    <p>
                        <a href="##" class="btn btn-primary">点击查看</a>
                    </p>
                </div>
            </div>
            <div class="col-md-3 col-xs-6">
                <a href="javascript:void(0);;" class="thumbnail">
                    <img src="img/a4.jpg" alt="">
                </a>
                <div class="caption">
                    <h4 class="h4">潭州教育软件学院</h4>
                    <p>潭州教育软件学院是一家在线互联网培训机构，公司已发展十年。目前已配置了完善的教育体系，覆盖全国各个行业，但是在线教育还是让学生跟老师互动困难...</p>
                    <p>
                        <a href="##" class="btn btn-primary">点击查看</a>
                    </p>
                </div>
            </div>
            <div class="col-md-3 col-xs-6">
                <a href="javascript:void(0);;" class="thumbnail">
                    <img src="img/a5.jpg" alt="">
                </a>
                <div class="caption">
                    <h4 class="h4">梦之梦科技有限公司</h4>
                    <p>梦之梦科技有限公司是一家小型的创业外包公司，公司由两位大牛创建。目前新增了一个互联线下培训项目，主要为希望从事互联行业的各种新人提供实战平台...</p>
                    <p>
                        <a href="##" class="btn btn-primary">点击查看</a>
                    </p>
                </div>
            </div>
           
        </div>

    </div>
    <!-- 登陆弹出框 -->
    <div id="enter_box" style="display: none;">
        <form>
            <div class="form-group">
                <label for="enter_user_name">用户名</label>
                <input type="text" id="enter_user_name" class="form-control" placeholder="请输入密码">
            </div>
            <div class="form-group">
                <label for="enter_user_password">密码</label>
                <input type="password" id="enter_user_password" class="form-control" placeholder="请输入密码">
            </div>
            <div id="enter_btn">
                <a href="javascript:void(0);" class="btn btn-success" id="enter_btn_enter">登陆</a>
                <a href="javascript:void(0);" class="btn btn-info" id="enter_btn_login">注册</a>
            </div>
        </form>
    </div>





<script type="text/javascript" src="quoteJs/bootstrap.js"></script>            
<script type="text/javascript" src="quoteJs/layui/layui.js" charset="utf-8"></script>
<script type="text/javascript" src="js/requirement4.js"></script>
</body>
</html>
