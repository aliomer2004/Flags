<?php
// --- كود PHP لمعالجة وحفظ التعليقات ---
$comments_file = 'comments.txt'; // اسم الملف الذي ستحفظ فيه التعليقات

// التأكد من أن المستخدم ضغط على زر إرسال
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = htmlspecialchars($_POST['name']); 
    $comment = htmlspecialchars($_POST['message']); 

    if (!empty($name) && !empty($comment)) {
        // تنسيق التعليق ليظهر داخل إطار HTML
        $new_comment = "<div class='user-comment'><strong>$name:</strong> $comment</div>\n";
        
        // حفظ التعليق في الملف النصي
        file_put_contents($comments_file, $new_comment, FILE_APPEND);
    }
}
?>

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>المملكة العربية السعودية</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <header>
            <h1>المملكة العربية السعودية</h1>
        </header>

        <section class="info">
            <h2>نبذة تعريفية</h2>
            <p>
                المملكة العربية السعودية هي دولة عربية إسلامية تقع في شبه الجزيرة العربية، وتعد أكبر دولة في الشرق الأوسط من حيث المساحة. 
                عاصمتها الرياض، وهي قبلة المسلمين لوجود المسجد الحرام والمسجد النبوي فيها. تتميز بمكانتها الاقتصادية العالمية بفضل احتياطيات النفط الضخمة، ورؤيتها الطموحة 2030.
            </p>
        </section>

        <section class="media">
            <div class="card">
                <h3>علم الدولة</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Flag_of_Saudi_Arabia.svg/800px-Flag_of_Saudi_Arabia.svg.png" alt="علم المملكة العربية السعودية">
            </div>

            <div class="card">
                <h3>خريطة الدولة</h3>
                <img src="https://m.media-amazon.com/images/I/51w+u2wX8cL._AC_UF1000,1000_QL80_.jpg" alt="خريطة المملكة العربية السعودية">
            </div>
        </section>

        <footer>
            <a href="https://ar.wikipedia.org/wiki/السعودية" target="_blank" class="wiki-btn">
                اضغط هنا للانتقال إلى صفحة ويكيبيديا الخاصة بالسعودية
            </a>
        </footer>

        <hr>

        <section class="comments-section">
            <h2>اترك تعليقاً</h2>
            
            <form action="index.php" method="POST" class="comment-form">
                <input type="text" name="name" placeholder="الاسم" required>
                <textarea name="message" placeholder="اكتب تعليقك هنا..." required></textarea>
                <button type="submit">إرسال</button>
            </form>

            <div class="comments-list">
                <h3>التعليقات السابقة:</h3>
                <?php
                if (file_exists($comments_file)) {
                    echo file_get_contents($comments_file);
                } else {
                    echo "<p style='color: #777;'>لا توجد تعليقات حتى الآن. كن أول من يعلق!</p>";
                }
                ?>
            </div>
        </section>

    </div>

</body>
</html>
