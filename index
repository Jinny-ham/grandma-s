<!DOCTYPE html>
<html lang="kr">
  <head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="keywords" content="진도,전라남도,전남,민박,펜션,하숙,여행,진도여행,관광,진도관광,지산면,세방낙조,진도지산면,진도군" />
    <meta name="description" content="진도사계절 민박은 진도 지산면 세방낙조로에 있는 민박입니다.">
    <title>진도 사계절 민박</title>
  </head>
  <body class="bg-light">
    <h1 class="m-3 btn btn-link btn-lg p-0"><a href="index.php" style="font-size: 3rem">진도 사계절 민박</a></h1>
    <div class="container m-3">
      <ul class="row justify-items-start nav nav-tabs btn-group col pr-0 mr-0">
        <?php
          $list = scandir('./data');
          $i = 0;
          while ($i < count($list)){
            if($list[$i] != '.'){
              if($list[$i] != '..'){
                echo "<li class=\"btn btn-secondary btn-sm nav-item col-6\"><a class=\"btn btn-secondary\"href=\"index.php?id=$list[$i]\">$list[$i]</a></li>";
              }
            }
            $i = $i + 1;
          }
         ?>
      </ul>
    </div>
    <div class="text-justify m-3">
        <h2><?php
        if(isset($_GET['id'])){
          echo $_GET['id'];
        } else {
          echo "안녕하세요";
        }; ?></h2>
        <p><?php
        if(isset($_GET['id'])){
           echo file_get_contents('data/'.$_GET['id']);
         } else {
           echo "진도 사계절 민박입니다.";
         }; ?></p>
    </div>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
