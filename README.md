# 扭蛋机介绍
[扭蛋机介绍.html](https://github.com/user-attachments/files/29117583/default.html)

<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>扭蛋机 - 语言切换</title>
    <style>
        /* 简单样式，可自行调整 */
        body {
            font-family: "Microsoft YaHei", sans-serif;
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background: #f9f9f9;
            color: #333;
        }
        .lang-buttons {
            text-align: center;
            margin-bottom: 30px;
        }
        .lang-buttons button {
            padding: 10px 30px;
            margin: 0 10px;
            font-size: 16px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            background: #007bff;
            color: white;
            transition: 0.2s;
        }
        .lang-buttons button:hover {
            background: #0056b3;
        }
        .lang-buttons button.active {
            background: #28a745;
            box-shadow: 0 0 0 2px #fff, 0 0 0 4px #28a745;
        }
        .content {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        .lang-zh, .lang-en {
            display: block;
        }
        .lang-zh.hidden, .lang-en.hidden {
            display: none;
        }
        .lang-en p, .lang-zh p {
            margin: 1em 0;
            line-height: 1.6;
        }
        .notice {
            background: #fff3cd;
            border-left: 6px solid #ffc107;
            padding: 10px 16px;
            margin: 16px 0;
        }
        code {
            background: #f4f4f4;
            padding: 2px 6px;
            border-radius: 4px;
            font-size: 0.9em;
        }
        hr {
            border: none;
            border-top: 1px solid #ddd;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <!-- 语言切换按钮 -->
    <div class="lang-buttons">
        <button id="btn-zh" class="active" onclick="switchLang('zh')">中文</button>
        <button id="btn-en" onclick="switchLang('en')">English</button>
    </div>

    <!-- 内容区域 -->
    <div class="content">
        <!-- 中文内容 -->
        <div id="lang-zh" class="lang-zh">
            <h2>自制扭蛋机网站</h2>
            <p>今天给大家分享一个很好玩的我自己做的网站——扭蛋机( <a href="http://chou.dongxiaozhan.top/login.html" target="_blank">chou.dongxiaozhan.top/login.html</a> )<br>
            |---账号: <strong>guest</strong> ---|<br>
            |--密码: <strong>123456</strong> --|<br>
            这个是账号密码，给大家作为公用账号免费体验</p>

            <div class="notice">
                <strong>「公用账号使用规则」</strong><br>
                1. 请不要将公用账号作为主力账号使用<br>
                2. 请勿修改密码，如果发现则封禁IP<br>
                3. 该账号不定时重置奖池、密码<br>
                4. 祝大家使用愉快，若需要专用账户请联系“微信:13503501032”
            </div>

            <hr>

            <p><strong>以下内容适合对电脑熟悉的用户进阶免费使用：</strong><br>
            源码的话是一个 HTML 文件<br>
            <a href="index.html" download="扭蛋机源码.html">文件</a><br>
            <span style="color: #d9534f;">注:本文件已停止支持,请勿过度依赖,新功能将不再添加。</span></p>

            <div class="notice">
                <strong>「使用注意事项」</strong><br>
                1. 本文件每次刷新/重新打开时奖池数据将恢复原数据，不会保存上次的奖池数据<br>
                2. 本文件已停止支持,请勿过度依赖,新功能将不再添加。
            </div>

            <hr>

            <p>冬冬(公益)开源®保留所有权利</p>
            <p>提供技术支持:<br>
            DeepSeek深度求索®,百度®AI 翻译,腾讯云®  在此感谢🙏</p>
            <p>若翻译错误请联系 XiaojiaoziD@icloud.com(邮箱) 或 Jiangyifanufo@163.com(邮箱)。</p>
        </div>

        <!-- 英文内容 -->
        <div id="lang-en" class="lang-en hidden">
            <h2>Homemade egg twisting machine website</h2>
            <p>Today, I would like to share with you a fun website that I have created myself - the egg twisting machine ( <a href="http://chou.dongxiaozhan.top/login.html" target="_blank">chou.dongxiaozhan.top/login.html</a> )<br>
            |----Account: <strong>guest</strong> ----|<br>
            |--Password: <strong>123456</strong> --|<br>
            This is the account password, for everyone to experience as a public account for free</p>

            <div class="notice">
                <strong>Public Account Usage Rules</strong><br>
                1. Please do not use public accounts as primary accounts<br>
                2. Do not change password, if found, ban IP address<br>
                3. The account will reset the prize pool and password from time to time<br>
                4. Wishing everyone a pleasant experience. If you need a dedicated account, please contact "WeChat: 13503501032"
            </div>

            <hr>

            <p><strong>The following content is suitable for advanced free use by users familiar with computers:</strong><br>
            The source code is an HTML file<br>
            <a href="index.html" download="扭蛋机源码.html">File</a><br>
            <span style="color: #d9534f;">Note: This document is no longer supported, please do not overly rely on it, new features will no longer be added.</span></p>

            <div class="notice">
                <strong>Precautions for use</strong><br>
                1. Each time this file is refreshed/reopened, the prize pool data will be restored to its original state and the previous prize pool data will not be saved<br>
                2. This document is no longer supported, please do not overly rely on it, new features will no longer be added.
            </div>

            <hr>

            <p>Dongdong (Public Welfare) Open Source ® All rights reserved</p>
            <p>Provide technical support:<br>
            DeepSeek AI®, Baidu® AI translation, Tencent Cloud®  Thank you here 🙏</p>
            <p>If there is a translation error, please contact XiaojiaoziD@icloud.com (Email) or Jiangyifanufo@163.com (Email).</p>
        </div>
    </div>

    <script>
        function switchLang(lang) {
            const zhDiv = document.getElementById('lang-zh');
            const enDiv = document.getElementById('lang-en');
            const btnZh = document.getElementById('btn-zh');
            const btnEn = document.getElementById('btn-en');

            if (lang === 'zh') {
                zhDiv.classList.remove('hidden');
                enDiv.classList.add('hidden');
                btnZh.classList.add('active');
                btnEn.classList.remove('active');
            } else {
                zhDiv.classList.add('hidden');
                enDiv.classList.remove('hidden');
                btnEn.classList.add('active');
                btnZh.classList.remove('active');
            }
        }
    </script>
</body>
</html>
