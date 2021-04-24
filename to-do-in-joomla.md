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