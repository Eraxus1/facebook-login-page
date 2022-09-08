<script>

</script>
<template>
    <center>
    <img src="facebook.svg" alt="" style="width:250px;">
    </center>
   
    <div class="signup-form">
        <form action="index.html">
            <h3>Yeni Bir Hesap Oluştur</h3>
            <p class="title">Hızlı ve kolaydır.</p>
            <hr>
            <div class="name">
                <input class="name-txt" type="text" placeholder="Adın">
                <input class="name-txt" type="text" placeholder="Soyadın">
            </div>
            <input type="email" class="txt" placeholder="Cep telefonu numarası veya e-posta">
            <input type="password" class="txt" placeholder="Yeni şifre">

            <div class="dogum-gun">
                <label for="dogum-gun">Doğum Tarihi</label>

            </div>
            <select class="dogumgun-input" id="">
                <option value="">1</option>
            </select>
            <select class="dogumgun-input" id="">
                <option value="">Eyl</option>
            </select>
            <select class="dogumgun-input" id="">
                <option value="">2022</option>
            </select>

            <div class="sex">
                <label for="cinsiyet">Cinsiyet</label>
                <button>Kadın</button>
                <button>Erkek</button>
                <button>Özel</button>
            </div>

            <p>
                Hizmetimizi kullanan kişiler senin iletişim bilgilerini Facebook'a yüklemiş olabilir.<a href="#">Daha fazla bilgi al</a>
            </p>
            <p>
                Kaydol düğmesine tıklayarak, Koşullarımızı, Gizlilik İlkemizi ve Çerezler İlkemizi kabul etmiş olursun. Bizden SMS Bildirimleri alabilir ve bu bildirimleri istediğin zaman durdurabilirsin.
            </p>

            <button class="register">Kaydol</button>
            <a class="register-a" href="#">Hesabın zaten var mı?</a>
        </form>
    </div>
</template>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #F0F2F5;
    font-family: Helvetica, Arial, sans-serif;
}

.title h1 {
    text-align: center;
    margin-top: 30px;
    color: #1877F2;
    font-size: 60px;
    font-weight: 750;
}

.signup-form {
    width: 425px;
    padding: 15px;
    background: #fff;
    position: absolute;
    left: 37%;
    top: 15%;
    padding:20px;
    box-shadow: 1px 2px 15px 1px rgba(0, 0, 0, 0.24);
    border-radius: 20px;
}

.signup-form h3 {
    font-size: 25px;
    line-height: 32px;
    text-align: center;
}

.signup-form .title {
    font-size: 15px;
    line-height: 24px;
    opacity: 0.7;
    text-align: center;
}

.signup-form hr {
    opacity: 0.5;
    width: 100%;
    margin-top: 7px;
}

.signup-form .name {
    display: flex;
}

.signup-form .name .name-txt {
    width: 190px;
    margin-top: 15px;
    height: 40px;
    padding: 5px;
    border-radius: 6px;
    margin-right: 10px;
    font-size: 15px;
    opacity: 0.5;
    border: 1px solid gray;
}

.txt {
    display: block;
    justify-content: center;
    width: 390px;
    height: 40px;
    padding: 5px;
    border-radius: 6px;
    font-size: 15px;
    opacity: 0.5;
    margin-top: 10px;
    border: 1px solid gray;

}

.signup-form .dogum-gun {
    display: block;
    font-size: 13px;
    opacity: 0.6;
    margin-top: 10px;
    
}
.signup-form .dogumgun-input{
    width: 30%;
    font-size: 15px;
    height: 40px;
    border-radius: 6px;
    margin-top: 4px;
    margin-right: 10px;
    border: 1px solid  #a9a9a9;

}
.signup-form .sex label{
    display: block;
    font-size: 13px;
    opacity: 0.6;
    margin-top: 10px;
}
.signup-form .sex button{
    width: 30%;
    height: 40px;
    background-color: #fff;
    border: 1px solid #a9a9a9;
    border-radius: 6px;
    margin-top: 6px;
    margin-right: 10px;
}
.signup-form p {
    font-size: 11px;
    text-align: justify;
    line-height: 15px;
    margin-top: 10px;
}
.signup-form a {
    text-decoration: none;
    color: #385898;
}
.signup-form .register {
    display: block;
    width: 200px;
    height: 40px;
    margin: auto;
    background: #119F16;
    border: none;
    border-radius: 10px;
    color: #fff;
    font-size: 20px;
    margin-top: 20px;
    font-weight: 700;
}
.signup-form .register-a {
   display: flex;
   justify-content: center;
   margin-top: 30px;
}

</style>