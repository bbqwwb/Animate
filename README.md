# Animate
通过计算滚动条滑动的位置控制animate的触发

    // Hidden...
   $(".revealOnScroll.animated").each(function (index) {
      var $this     = $(this),
          offsetTop = $this.offset().top;
      if (scrolled + win_height_padded < offsetTop) {
        $(this).removeClass('animated fadeInLeft fadeInRight fadeInDown bounce pulse')
      }
    });
