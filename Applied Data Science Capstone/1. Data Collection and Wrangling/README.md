.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
<div class="row">
  <div class="column">
    <img src="landing_1.gif" alt="Landing" style="width:100%">
  </div>
  <div class="column">
    <img src="crash.gif" alt="Crash" style="width:100%">
  </div>
</div>
