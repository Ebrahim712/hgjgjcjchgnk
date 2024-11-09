<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=edge"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>السايله نت</title>
    <style>
        body {background-color: #ADD8E6; font-family: Arial, sans-serif; margin: 0; padding: 0; color: black;}
        h1 {color: red; text-align: center; margin-top: 50px; font-size: 36px; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);}
        .logo {vertical-align: middle; width: 30px; height: auto;}
        .icons {text-align: center; margin-top: 10px;}
        .icons i {font-size: 30px; margin-left: 10px; transition: color 0.3s;}
        .icons i:hover {color: gold;}
        #login-window {width: 300px; height: 200px; background-color: white; margin: 50px auto; padding: 20px; border-radius: 10px; box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); text-align: center; animation: slide-in 2s forwards;}
        @keyframes slide-in {from {transform: translateY(-100%);} to {transform: translateY(0);}}
        #card-number {padding: 10px; font-size: 16px; width: 80%; margin: 10px 0; border: 1px solid #ccc; border-radius: 5px; transition: border-color 0.3s;}
        #card-number:focus {border-color: gold;}
        .green-text {color: darkgreen; text-align: center; font-size: 20px; margin-top: 30px;}
        table {width: 50%; margin: 30px auto; border-collapse: collapse; border: 1px solid black;}
        table th, table td {padding: 10px; text-align: center; border: 1px solid black;}
        table th {background-color: #f2f2f2;}
        #register-btn {background-color: red; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; font-size: 16px; margin-top: 20px;}
        #register-btn:hover {background-color: darkred;}
        @media screen and (max-width: 600px) {table {width: 100%;} #login-window {width: 80%;} h1 {font-size: 28px;}}
        .footer-text {font-size: 12px; text-align: center; margin-top: 50px; color: black;}
        .warning-message, .success-message {color: black; font-size: 18px; font-weight: bold; display: none; text-align: center; margin-top: 20px; padding: 20px; border-radius: 10px;}
        .warning-message {background-color: #ADD8E6; border: 2px solid #0099cc;}
        .success-message {background-color: #ADD8E6; border: 2px solid #008000;}
        #confirm-btn {background-color: green; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer;}
        #confirm-btn:hover {background-color: darkgreen;}
    </style>
</head>
<body>
    <div class="green-text">أهلاً وسهلاً بكم في السايله نت! نحن هنا لخدمتك.</div>
    <h1><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Water_drop_icon.svg/1200px-Water_drop_icon.svg.png" class="logo" alt="مياه"> السايله نت</h1>
    <div class="icons"><i class="fa fa-wifi"></i><i class="fa fa-bolt"></i></div>
    <div id="login-window"><h2 style="color: red;">دخول الشبكة</h2><input type="text" id="card-number" placeholder="كم تشتي تسقي" oninput="showWarningMessage()"><button id="register-btn" onclick="showWarningMessage()">تسجيل</button></div>
    
    <!-- رسالة التحذير -->
    <div class="warning-message" id="warning-message">
        عذراً عزيزي المشترك، لا يمكنك السقي الآن. انتظر يوم أو يومين.
        <button id="confirm-btn" onclick="showSuccessMessage()">موافق</button>
    </div>
    
    <!-- رسالة النجاح -->
    <div class="success-message" id="success-message">
        لقد تم تسجيلكم في القائمة، سيتم إعلامكم في أقرب وقت. شكراً لكم.
    </div>
    
    <div class="green-text">اسعار الديزل</div>
    <table><tr><th>سعر الديزل</th><th>الوقت المتاح</th></tr><tr><td>دبه 20 لتر</td><td>ساعتين ونص</td></tr><tr><td>دبه 10 لتر</td><td>ساعه وربع</td></tr></table>
    <div class="footer-text">إعداد المهندس إبراهيم صالح موسى<br>للتواصل اتصل على الرقم التالي 779125732.</div>
    
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/js/all.min.js"></script>
    <script>
        function showWarningMessage() {
            document.getElementById('warning-message').style.display = 'block';
        }

        function showSuccessMessage() {
            document.getElementById('warning-message').style.display = 'none';
            document.getElementById('success-message').style.display = 'block';
        }
    </script>
</body>
</html>
