# Sass_test-
practical use
html要link由sass產出的css
寫法是巢狀結構:

$red:red;
.container{

}.row{

}.text{
    color: $red;
}.txt{
    color: blue;
}

第二個row 如果是用css寫就是.container.row

如果有常用的就會先設定變數:$red:red; 然後看哪邊會用到 就套用$red

在sass寫完樣式之後 重新存檔就可以更新做的事情了 前提是你watching有打開

假如sass這樣寫      &在sass是繼承副層的意思
.container{

}&:before

就等於css如下    

.container{

}

.container:before{

}
