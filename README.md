# Free Bootstrap Breadcrumb Component

Indicate the current page’s location within a navigational hierarchy that automatically adds separators via CSS.

<p><strong>How to use it?</strong></p>
<p class="mb-2">
<strong>1. </strong>Download<a target="_blank" href="https://mdbootstrap.com/docs/standard/"> MDB 5 - free UI KIT</a></p>
<p class="mb-2"><strong>2. </strong>Choose your favourite customized example and click <code>show code</code> to see the code</p>
<p class="mb-3"><strong>3. </strong>Copy & paste the code into your MDB project</p>

--------------------

[📄 **Documentation & usage guide**](https://mdbootstrap.com/docs/standard/navigation/breadcrumb/)

These components were built with a **free Material Design UI Kit for the latest Bootstrap 5**.

<img height="25" src="https://mdbootstrap.com/img/Marketing/general/logo/medium/mdb-r.png">  [![GitHub Stars](https://img.shields.io/github/stars/mdbootstrap/mdb-ui-kit?label=Star%20now&style=social)](https://github.com/mdbootstrap/mdb-ui-kit/)

---------------------

 <h2 class="mb-4">Basic example</h2> 
 
```html

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item active" aria-current="page">Home</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item active" aria-current="page">Library</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item"><a href="#">Library</a></li>
    <li class="breadcrumb-item active" aria-current="page">Data</li>
  </ol>
</nav>

```

 
 <hr class="my-5">
 
 <h2 class="mb-4">Breadcrumb in navbar</h2> 
 
```html
<nav data-mdb-navbar-init class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="#">Home</a></li>
        <li class="breadcrumb-item"><a href="#">Library</a></li>
        <li class="breadcrumb-item active" aria-current="page"><a href="#">Data</a></li>
      </ol>
    </nav>
  </div>
</nav>
```

 <hr class="my-5">
 
 <h2 class="mb-4">Breadcrumb in header
</h2> 
 
```html
<!--Main Navigation-->
<header>

  <!-- Navbar -->
  <nav id="main-navbar" class="navbar navbar-expand-lg bg-body">
    <!-- Container wrapper -->
    <div class="container-fluid">

      <!-- Search form -->
      <form class="d-none d-md-flex input-group w-auto my-auto">
        <input autocomplete="off" type="search" class="form-control rounded" placeholder='Search (ctrl + "/" to focus)'
          style="min-width: 225px" />
        <span class="input-group-text border-0"><i class="fas fa-search"></i></span>
      </form>

      <!-- Right links -->
      <ul class="navbar-nav ms-auto d-flex flex-row">
        <!-- Notification dropdown -->
        <li class="nav-item dropdown">
          <a data-mdb-dropdown-init class="nav-link me-3 me-lg-0 dropdown-toggle hidden-arrow" href="#" id="navbarDropdownMenuLink"
            role="button" aria-expanded="false">
            <i class="fas fa-bell"></i>
            <span class="badge rounded-pill badge-notification bg-danger">1</span>
          </a>
          <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">Some news</a></li>
            <li><a class="dropdown-item" href="#">Another news</a></li>
            <li>
              <a class="dropdown-item" href="#">Something else here</a>
            </li>
          </ul>
        </li>

        <!-- Icon dropdown -->
        <li class="nav-item dropdown">
          <a data-mdb-dropdown-init class="nav-link me-3 me-lg-0 dropdown-toggle hidden-arrow" href="#" id="navbarDropdown" role="button" aria-expanded="false">
            <i class="flag-united-kingdom flag m-0"></i>
          </a>
          <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navbarDropdown">
            <li>
              <a class="dropdown-item" href="#"><i class="flag-united-kingdom flag"></i>English
                <i class="fa fa-check text-success ms-2"></i></a>
            </li>
            <li>
              <hr class="dropdown-divider" />
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-poland flag"></i>Polski</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-china flag"></i>中文</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-japan flag"></i>日本語</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-germany flag"></i>Deutsch</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-france flag"></i>Français</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-spain flag"></i>Español</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-russia flag"></i>Русский</a>
            </li>
            <li>
              <a class="dropdown-item" href="#"><i class="flag-portugal flag"></i>Português</a>
            </li>
          </ul>
        </li>

        <!-- Avatar -->
        <li class="nav-item dropdown">
          <a data-mdb-dropdown-init class="nav-link dropdown-toggle hidden-arrow d-flex align-items-center" href="#"
            id="navbarDropdownMenuLink" role="button" aria-expanded="false">
            <img src="https://mdbootstrap.com/img/new/avatars/2.jpg" class="rounded-circle" height="22" alt="Avatar"
              loading="lazy" />
          </a>
          <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="navbarDropdownMenuLink">
            <li><a class="dropdown-item" href="#">My profile</a></li>
            <li><a class="dropdown-item" href="#">Settings</a></li>
            <li><a class="dropdown-item" href="#">Logout</a></li>
          </ul>
        </li>
      </ul>
    </div>
    <!-- Container wrapper -->
  </nav>
  <!-- Navbar -->

  <!-- Heading -->
  <div class="p-5 bg-body-tertiary mb-4">
    <h1 class="">Dashboard</h1>
    <!-- Breadcrumb -->
    <nav class="d-flex">
      <h6 class="mb-0">
        <a href="" class="text-reset">Home</a>
        <span>/</span>
        <a href="" class="text-reset">Analytics</a>
        <span>/</span>
        <a href="" class="text-reset"><u>Dashboard</u></a>
      </h6>
    </nav>
    <!-- Breadcrumb -->
  </div>
  <!-- Heading -->
</header>
<!--Main Navigation-->

```

```javascript
// Initialization for ES Users
import { Dropdown, initMDB } from "mdb-ui-kit";

initMDB({ Dropdown });
```
 <hr class="my-5">
 <h2 class="mb-4">Changing the separator
</h2> 
 
```scss
$breadcrumb-divider: quote(">");

```

```scss
$breadcrumb-divider: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg'
width='8' height='8'%3E%3Cpath d='M2.5 0L1 1.5 3.5 4 1 6.5 2.5 8l4-4-4-4z'
fill='currentColor'/%3E%3C/svg%3E");
```

```scss
$breadcrumb-divider: none;
```
 <hr class="my-5">
 
 <h2 class="mb-4">Accessibility</h2> 
 
Since breadcrumbs provide a navigation, it’s a good idea to add a meaningful label such as <code>aria-label="breadcrumb"</code> to describe the type of navigation provided in the <code>nav</code> element, as well as applying an <code>aria-current="page"</code> to the last item of the set to indicate that it represents the current page.

For more information, see the [WAI-ARIA Authoring Practices for the breadcrumb pattern](https://www.w3.org/TR/wai-aria-practices/#breadcrumb).


