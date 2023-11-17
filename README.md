# jquery 기본 연습

- mockaroo 목업데이타 사이트
- https://www.mockaroo.com/


## jquery basic
- animate()
```
$('.btn1').on('click', function() {
            $('.text1').animate({marginLeft: 500, fontSize: 30}, 2000, function(){
                alert('hello?')
            })
})
```

- fade()

```
        $('.btn1').on('click', function(){
            $('.box').slideUp(1000, 'linear', function() {
                $('.btn1').hide()
                $('.btn2').show()
            })
        })
```

### 선택자

- 기본선택자
- 탐색선택자
- 속성선택자

