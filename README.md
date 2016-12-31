# Cascading-
Style-Sheets
### CSS学习  
```
<style>
        /* 标签选择器 */
        div{
            color: red;
        }

        p{
            color: blue;
        }

        /* 类选择器 */
        .test1{
           color: green;
        }

        /*id选择器*/
        #main{
            font-size: 40px;
        }

        /*并列选择器*/
        #main, .test1{
           border: 1px solid rosybrown;
        }

        /*复合选择器*/
        p.test1{
            background-color: yellow;
        }

        /*后代选择器*/
        div a{
            color: red;
        }

        /*直接后代选择器*/
        div.test1>a{
           color: green;
        }

        /*伪类*/
        input:focus{
            /*去除外线条*/
            outline: none;
            /*改变宽度和高度*/
            width: 500px;
            height: 50px;
            /*改变文字的大小*/
            font-size: 20px;
        }

        /*当鼠标移动上来*/
        #main:hover{
            width: 300px;
            height: 200px;
            background-color: aqua;
        }
```
