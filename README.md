# 14.animation
## program :
```
<!DOCTYPE html>
<html>
  <head>
    <title>animation example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="content">
    <h2>hello world</h2>
    </div>
  </body>
</html>
body{
  background-color:#f0f0f0;
}.content{
  display: grid;
  place-items:center;
}
@keyframes moveinfo{
  from{
    transform:translateY(-100px);
  }
  to{
    transform:translateY(0px);
  }
}
h2{
  animation-name:moveinfo;
  animation-iteration-count:3;
  animation-timing-function:;
  animation-duration: 3s;
}
```
# output :
![WhatsApp Image 2024-07-14 at 22 49 54_fc06fda7](https://github.com/user-attachments/assets/3fd831b4-e068-4565-91e5-a38936d6a9e4)
