# TestRepo

.parent {
display: grid;
grid-template-columns: repeat(3, 1fr);
grid-template-rows: repeat(6, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
}

.div1 { grid-area: 1 / 1 / 2 / 6; }
.div2 { grid-area: 2 / 2 / 7 / 4; }
.div3 { grid-area: 2 / 1 / 7 / 2; }



<div class="parent">
<div class="div1"> </div>
<div class="div2"> </div>
<div class="div3"> </div>
</div>



