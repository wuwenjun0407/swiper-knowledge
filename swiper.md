# swiper

@(swiper)


## 用法：
>swiper的HTML固定结构
```
<div class="swiper-container">
  <div class="swiper-wrapper">
    <div class="swiper-slide">slider1</div>
    <div class="swiper-slide">slider2</div>
    <div class="swiper-slide">slider3</div>
  </div>
</div>

```
### 1.通过new方式创建一个swiper的实例
>autoplay：默认是0。不管加不加时间，都能实现手指滑动的效果。
>initialSlide：slide图片的索引，就是刚打开页面显示的是第几张图片，但是开始轮播的时候，还是从索引一开始。
>speed：图片移动的速度
>loop：反方向自动切换
```
var mySwiper=new Swiper('.swiper-container',{
		autoplay:2000，//自动轮播，间隔时间是2秒
		initialSlide：2，
		loop：true，
		de
		speed：300，
	})
```