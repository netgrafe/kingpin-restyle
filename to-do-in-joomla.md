# Joomla-ban kell majd átállítani

- törölni a k2style.css-t mert teljesen azonos a joomla.css -el, ki kell venni a HTML-ből is
- törölni index.php-ból:
```
#fav-container {
    background-repeat: repeat; 
}
```

- levenni a `fav-logo` és `fav-nav` elemekről a bootstrap-es spanXX classokat
    - flexbox-al lesz megoldva helyette
- átírni a LOGO-n az alt="" tag érétkét

- a mobil menü nyitó részét átírni:
    - collapsed kerüljön rá egyből
    - két FontAwesome icon
```
div class="navbar navbar-inverse">
    <div class="navbar-inner">
        <a class="btn btn-navbar collapsed" data-toggle="collapse" data-target=".nav-collapse">
            <i class="icon fa fa-bars"></i>
            <i class="icon fa fa-times"></i>
        </a>
```