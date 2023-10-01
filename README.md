# practice
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bootstrap demo</title>
  <link rel="stylesheet" href="pratical-style.css">
  <script src="https://kit.fontawesome.com/fb27a425b2.js" crossorigin="anonymous"></script>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>
  <!-- Option 2: Separate Popper and Bootstrap JS -->
  <!--
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.min.js" integrity="sha384-+sLIOodYLS7CIrQpBjl+C7nPvqq+FbNUBDunl/OZv93DB7Ln/533i8e/mZXLi/P+" crossorigin="anonymous"></script>
  -->
</head>
<body>
<header class="navbar flex-column navbar-expend">
  <div class="fixed-top shadow">
    <div class="collapse" id="navbarToggleExternalContent">
      <div class="bg-primary p-3">
        <h5 class="text-white h2">관리자 페이지</h5>
        <span class="font-weight-bold small text-white">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam, architecto consequatur culpa doloremque in iste libero magnam modi neque perferendis perspiciatis quos repellendus tenetur unde ut vel voluptas? Et, iusto.</span>
      </div>
    </div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-toggle="dropdown" aria-expanded="false">
              Dropdown
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Disabled</a>
          </li>
        </ul>
      </div>
      <form class="navbar-expand navbar-nav form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </nav>
  </div>
</header>

<div class="container-fluid bg-light">
  <div class="row flex-xl-nowrap">
    <div class="d-flex flex-column flex-shrink-0 bg-light" style="width: 4.5rem;">
      <a href="/" class="d-block p-3 link-dark text-decoration-none" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Icon-only">
        <svg class="bi" width="40" height="32"><use xlink:href="#bootstrap"></use></svg>
        <span class="visually-hidden">Icon-only</span>
      </a>
      <ul class="nav nav-flush flex-column mb-auto text-center">
        <li class="nav-item">
          <a href="#" class="nav-link active py-3 border-bottom" aria-current="page" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Home">
            <i class="fa-solid fa-house"><use xlink:href="#home"></use></i>
          </a>
        </li>
        <li>
          <a href="#" class="nav-link py-3 border-bottom" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Dashboard">
            <i class="fa-solid fa-chart-line"><use xlink:href="#speedometer2"></use></i>
          </a>
        </li>
        <li>
          <a href="#" class="nav-link py-3 border-bottom" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Orders">
            <i class="fa-regular fa-calendar-check"><use xlink:href="#table"></use></i>
          </a>
        </li>
        <li>
          <a href="#" class="nav-link py-3 border-bottom" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Products">
            <i class="fa-regular fa-window-restore"><use xlink:href="#grid"></use></i>
          </a>
        </li>
        <li>
          <a href="#" class="nav-link py-3 border-bottom" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Customers">
            <i class="fa-solid fa-circle-user"><use xlink:href="#people-circle"></use></i>
          </a>
        </li>
      </ul>
      <div class="dropdown border-top">
        <a href="#" class="d-flex align-items-center justify-content-center p-3 link-dark text-decoration-none dropdown-toggle" id="dropdownUser3" data-bs-toggle="dropdown" aria-expanded="false">
          <img src="https://github.com/mdo.png" alt="mdo" width="24" height="24" class="rounded-circle">
        </a>
        <ul class="dropdown-menu text-small shadow" aria-labelledby="dropdownUser3">
          <li><a class="dropdown-item" href="#">New project...</a></li>
          <li><a class="dropdown-item" href="#">Settings</a></li>
          <li><a class="dropdown-item" href="#">Profile</a></li>
          <li><hr class="dropdown-divider"></li>
          <li><a class="dropdown-item" href="#">Sign out</a></li>
        </ul>
      </div>
    </div>
    <main style="position: relative;" class="col-md-9 col-xl-8 py-md-3 pl-md-5 bd-content bg-light" role="main">
      <div class="card shadow-sm p-3 mb-5 bg-white rounded border-0" style="margin-top: 80px;">

        <div class="card-body">
          <h5 class="card-title">신규가입회원 5건 목록</h5>
          <div class="p-3 mb-2 bg-light text-dark">회원수 1명 중 차단 0명, 탈퇴 5명</div>
          <table style="margin-top: 8px;" class="table table-striped table-hover">
            <thead class="table-dark">
            <tr>
              <th scope="col">회원아이디</th>
              <th scope="col">이름</th>
              <th scope="col">닉네임</th>
              <th scope="col">권한</th>

              <th scope="col">포인트</th>
              <th scope="col">권한</th>
              <th scope="col">수신</th>
              <th scope="col">공개</th>

              <th scope="col">인증</th>
              <th scope="col">차단</th>
              <th scope="col">그룹</th>
            </tr>
            </thead>
            <tbody>
            <tr>
              <th scope="row">admin</th>
              <td>최고관리자</td>
              <td>최고관리자</td>
              <td>10</td>
              <td>1,150</td>
              <td>예</td>
              <td>예</td>
              <td>예</td>
              <td>아니오</td>
              <td>-</td>
              <td>-</td>
            </tr>
            </tbody>
          </table>
          <a href="#" class="btn btn-primary" style="float: right;">회원 전체보기</a>
        </div>
      </div>

      <div class="card shadow-sm p-3 mb-5 bg-white rounded border-0" style="margin-top: 80px;">

        <div class="card-body">
          <h4 class="card-title">최근 게시물</h4>

          <table style="margin-top: 10px" class="table table-striped table-hover">
            <thead class="table-dark">
            <tr>
              <th scope="col">회원아이디</th>
              <th scope="col">이름</th>
              <th scope="col">닉네임</th>
              <th scope="col">권한</th>

              <th scope="col">포인트</th>
              <th scope="col">권한</th>
              <th scope="col">수신</th>
              <th scope="col">공개</th>

              <th scope="col">인증</th>
              <th scope="col">차단</th>
              <th scope="col">그룹</th>
            </tr>
            </thead>
            <tbody>
            <tr>
              <th scope="row">admin</th>
              <td>최고관리자</td>
              <td>최고관리자</td>
              <td>10</td>
              <td>1,150</td>
              <td>예</td>
              <td>예</td>
              <td>예</td>
              <td>아니오</td>
              <td>-</td>
              <td>-</td>
            </tr>
            <tr>
              <th scope="row">admin</th>
              <td>최고관리자</td>
              <td>최고관리자</td>
              <td>10</td>
              <td>1,150</td>
              <td>예</td>
              <td>예</td>
              <td>예</td>
              <td>아니오</td>
              <td>-</td>
              <td>-</td>
            </tr>
            <tr>
              <th scope="row">admin</th>
              <td>최고관리자</td>
              <td>최고관리자</td>
              <td>10</td>
              <td>1,150</td>
              <td>예</td>
              <td>예</td>
              <td>예</td>
              <td>아니오</td>
              <td>-</td>
              <td>-</td>
            </tr>
            </tbody>
          </table>
          <a href="#" class="btn btn-primary" style="float: right;">회원 전체보기</a>
        </div>
      </div>
    </main>
  </div>

</div>

</body>
</html>
