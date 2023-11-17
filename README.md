# jquery 기본 연습

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
