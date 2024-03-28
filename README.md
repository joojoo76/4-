<!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="utf-8">
        <meat http-equiv="X-UA-Compatible" content="IE=edge">
        <title>채팅방 만들기</title>
        <link href="chat.css" rel="stylesheet">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+KR&display=swap" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <main class="chat-screen">
                <section class="chat-screen__bar">
                    <div class="user">
                        <div class="user__column">
                            <div class="user__pic"></div>
                        </div>
                        <div class="user__column">
                            <p class="user__nick">친구</p>
                            <p class="user__count">2</p>
                        </div>
                    </div>
                </section>
            </main>

            <form class="chat-from">
                <section class="chat-from__field">
                <textarea class="chat-from__msg"></textarea>
                <input type="submit" value="전송" class="chat-from__bt">
                
                </section>
            </form>
        </div>

    </body>
</html>
