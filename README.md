# simple-server-startpage
A simple webpage to access admin consoles for services running on my home server.

## Easily expandable
### Adjust number of columns
Change the number of columns by adding/removing an `auto` from `grid-template-columns`.
```
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  padding: 15x;
}
```
### Add link
Add a `grid-container` object to the body, changing url and icon as needed.
```
<div class="grid-container">
  <div class="grid-item">
    <a href="http://192.168.1.91:3000">
      <img src = images/grafana.svg height="150" width="150"><br>
         <div class = label>Grafana</div>
    </a>
  </div>
```

