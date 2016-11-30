# projeto-oi

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.


# Todos

1- small fix on first screen (login)

.start > .title,
.start > .fp-tableCell > .title{
    margin-top : 0 !important;
    font-size: 28px;
}


.telephone > .title,
.telephone > .fp-tableCell > .title,
.wifi > .title,
.wifi > .fp-tableCell > .title
{
  font-size: 21px;
}



.wifi > .btn_connection,
.wifi > .fp-tableCell > .btn_connection{
  width: 270px;
  height: 70px;
  border-radius: 3px;
  background-color: #ffffff;
  border: solid 1px #e03d6f;
  font-size: 21px;
  letter-spacing: -0.5px;
  text-align: center;
  color: #e03d6f;
  margin-bottom: 20px;
}

.wifi > .footer,
.wifi > .fp-tableCell > .footer{
  width : 518px;
  font-size: 21px;
  line-height: 1.43;
  letter-spacing: -0.8px;
  color: #222222;
}

#recharge{
    height: 100vh !important;
}

/* oiplay and recharge */

.oiplay > .title , 
.recharge > .title ,
.oiplay > .fp-tableCell > .title , 
.recharge > .fp-tableCell > .title 
{
  font-size: 42px;
  letter-spacing: -1.5px;
  color: #222222;
  margin-bottom: 36px;
}

.oiplay > .content , 
.oiplay > .fp-tableCell > .content , 
.recharge > .content ,
.recharge > .fp-tableCell > .content{
  width: 640px;
  font-size: 28px;
  font-style: normal;
  font-stretch: normal;
  line-height: 1.25;
  letter-spacing: -1.1px;
  color: #222222;
}

.oiplay > .btn_oiplay ,
.recharge > .btn_recharge,
.oiplay > .fp-tableCell > .btn_oiplay ,
.recharge > .fp-tableCell > .btn_recharge{
  width: 270px;
  height: 70px;
  border-radius: 3px;
  font-size: 21px;
  letter-spacing: -0.5px;
  background-color: #ffffff;
  border: solid 1px #e03d6f;
  text-align: center;
  color: #e03d6f;
  margin-bottom: 20px;
}

.oiplay > .footer ,
.recharge > .footer
.oiplay > .fp-tableCell > .footer ,
.recharge > .fp-tableCell > .footer{
  font-size: 21px;
  line-height: 1.43;
  letter-spacing: -0.8px;
  color: #222222;
}

/* faq */
.help{ /* enable scroll */
    * overflow-y: scroll;
}

.help > .title,
.help > .fp-tableCell > .title{
  margin-top: 76px;
  font-size: 42px;
  letter-spacing: -1.5px;
  color: #222222;
  margin-bottom: 42px;
}

/* custom li */
.help > .content > ol ,
.help > .fp-tableCell > .content > ol{ 
    counter-reset: item;
    padding-left: 0px;
}


ol div li { display: block; }
.custom-li:before{
    font-size: 28px;
    line-height: 1.25;
    letter-spacing: -1.1px;
    color: #777777;
    content: counter(item) ". ";
    counter-increment: item;
    margin-right: 28px;
    margin-left: 0px;
}
.custom-li {
    font-size: 28px;
    line-height: 1.25;
    letter-spacing: -1.1px;
    color: #222222;
    margin-left: 0px !important;
    padding-left: 0px !important;
}

/* item */
.help > .content > ol > .item,
.help > .fp-tableCell > .content > ol > .item{
    border-top: solid 1px #dddddd;
    border-bottom: solid 1px #dddddd;
    padding-top: 33px;
    padding-bottom: 33px;
    margin-right: 70px;
}

/* internal intent content, inside collapse */
.help > .content > ol > .item > .collapse,
.help > .content > ol > .item > .collapsing,
.help > .content > ol > .item > .collapse.in,
.help > .fp-tableCell > .content > ol > .item > .collapse,
.help > .fp-tableCell > .content > ol > .item > .collapsing,
.help > .fp-tableCell > .content > ol > .item > .collapse.in
{
    width: 640px;
    font-size: 18px;
    line-height: 1.33;
    letter-spacing: -0.2px;
    color: #222222;
    margin-left: 38px;
    margin-top: 14px;
    margin-bottom: 42px;
}

.help > .footer,
.help > .fp-tableCell > .footer{
  font-size: 28px;
  line-height: 1.25;
  letter-spacing: -1.1px;
  color: #222222;
  margin-top: 67px;
  margin-bottom: 99px !important;
}

.help > .footer > span,
.help > .fp-tableCell > .footer > span{
    color: #e03d6f;
}

.help_item_center,
{
    height: 100%;
}

/* help center float content and show background img */
.arrow_item_help + .img_container_help{
    height: 10px;
    width: 23px;
    text-align: right;
    margin-left: auto;
    float: right;
    clear: right;
    background-image: url(../svg/arrow_up.svg)
}

.arrow_item_help.collapsed + .img_container_help{
    height: 10px;
    width: 23px;
    text-align: right;
    margin-left: auto;
    float: right;
    clear: right;
    background-image: url(../svg/arrow_down.svg) !important
}




/* background img of arrow */
.arrow_item_help{
    /* display: flex;
    align-items: center; */
    display: inline-block;
    vertical-align: middle;
}

/* hover button on dashboard page */
.btn_hover_dash:hover,
.btn_hover_dash:focus,
.btn_hover_dash:active
{
    border-radius: 3px;
    background-color: #e03d6f;
    border: solid 1px #ffffff;
    color: white;
    outline: 0;
}
