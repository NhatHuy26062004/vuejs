<template>
  <!-- Site footer -->
  <footer class="site-footer">
    <div class="container">
      <div class="row">
        <div class="col-sm-12 col-md-6">
          <h6>Thông tin</h6>
          <p class="text-justify">Scanfcode.com <i>CODE WANTS TO BE SIMPLE </i> is an initiative  to help the upcoming programmers with the code. Scanfcode focuses on providing the most efficient code or snippets as the code wants to be simple. We will help programmers build up concepts in different programming languages that include C, C++, Java, HTML, CSS, Bootstrap, JavaScript, PHP, Android, SQL and Algorithm.</p>
        </div>

        <div class="col-xs-6 col-md-3">
          <h6>Điều khoản</h6>
          <ul class="footer-links">
            <li><a href="">Điều khoản sử dụng</a></li>
            <li><a href="">Chính sách bảo mật thông tin</a></li>
            <li><a href="">Hướng dẫn xuất hóa đơn</a></li>

          </ul>
        </div>

        <div class="col-xs-6 col-md-3">
          <h6>Giới thiệu</h6>
          <ul class="footer-links">
            <li><a href="http://scanfcode.com/about/">Về chúng tôi</a></li>
            <li><a href="http://scanfcode.com/contact/">Sản phẩm</a></li>
            <li><a href="http://scanfcode.com/contribute-at-scanfcode/">Khuyến mãi</a></li>
            <li><a href="http://scanfcode.com/privacy-policy/">Cửa hàng</a></li>
            <li><a href="http://scanfcode.com/sitemap/">Tuyển dụng</a></li>
          </ul>
        </div>
      </div>
      <hr>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-sm-6 col-xs-12">
          <p class="copyright-text">Copyright &copy; 2017 All Rights Reserved by
       <a href="#" class="text-dark">Banh Xác</a>
          </p>
        </div>
      </div>
    </div>
</footer>

  </template>
  
  <script>
  export default {
    name: 'FooterComponent'
  }
  </script>
  
  <style scoped>
  .site-footer {
    background-image: url('https://thanhnamfood.vn/assets/images/image/bg_ft.png');
    background-size: cover; 
    background-repeat: no-repeat; 
    padding: 45px 0 20px;
    font-size: 15px;
    line-height: 24px;
    color: rgb(253, 251, 251);
  }
  .site-footer hr
  {
    border-top-color:#faf5f5;
    opacity:0.5
  }
  .site-footer hr.small
  {
    margin:20px 0
  }
  .site-footer h6
  {
    color:#fff;
    font-size:16px;
    text-transform:uppercase;
    margin-top:5px;
    letter-spacing:2px
  }
  .site-footer a
  {
    color:#f9f6f6;
  }
  .site-footer a:hover
  {
    color:#3366cc;
    text-decoration:none;
  }
  .footer-links
  {
    padding-left:0;
    list-style:none
  }
  .footer-links li
  {
    display:block
  }
  .footer-links a
  {
    color:rgb(249, 247, 247);
  }
  .footer-links a:active,.footer-links a:focus,.footer-links a:hover
  {
    color:#3366cc;
    text-decoration:none;
  }
  .footer-links.inline li
  {
    display:inline-block
  }
  .site-footer .social-icons
  {
    text-align:right
  }
  .site-footer .social-icons a
  {
    width:40px;
    height:40px;
    line-height:40px;
    margin-left:6px;
    margin-right:0;
    border-radius:100%;
    background-color:#33353d
  }
  .copyright-text
  {
    margin:0
  }
  @media (max-width:991px)
  {
    .site-footer [class^=col-]
    {
      margin-bottom:30px
    }
  }
  @media (max-width:767px)
  {
    .site-footer
    {
      padding-bottom:0
    }
    .site-footer .copyright-text,.site-footer .social-icons
    {
      text-align:center
    }
  }
  .social-icons
  {
    padding-left:0;
    margin-bottom:0;
    list-style:none
  }
  .social-icons li
  {
    display:inline-block;
    margin-bottom:4px
  }
  .social-icons li.title
  {
    margin-right:15px;
    text-transform:uppercase;
    color:#96a2b2;
    font-weight:700;
    font-size:13px
  }
  .social-icons a{
    background-color:#eceeef;
    color:#818a91;
    font-size:16px;
    display:inline-block;
    line-height:44px;
    width:44px;
    height:44px;
    text-align:center;
    margin-right:8px;
    border-radius:100%;
    -webkit-transition:all .2s linear;
    -o-transition:all .2s linear;
    transition:all .2s linear
  }
  .social-icons a:active,.social-icons a:focus,.social-icons a:hover
  {
    color:#fff;
    background-color:#29aafe
  }
  .social-icons.size-sm a
  {
    line-height:34px;
    height:34px;
    width:34px;
    font-size:14px
  }
  .social-icons a.facebook:hover
  {
    background-color:#3b5998
  }
  .social-icons a.twitter:hover
  {
    background-color:#00aced
  }
  .social-icons a.linkedin:hover
  {
    background-color:#007bb6
  }
  .social-icons a.dribbble:hover
  {
    background-color:#ea4c89
  }
  @media (max-width:767px)
  {
    .social-icons li.title
    {
      display:block;
      margin-right:0;
      font-weight:600
    }
  }
  
  </style>
  