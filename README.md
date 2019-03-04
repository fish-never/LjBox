# LjBox
//如下调用
var ljbox = new LjBox({
    tmpId: 'dialogTpl',
    cancel: true,
    content: 'hello world!'
});
LjBox.on('confirm',function(ev){
    console.log('you click confirm!');
    // 写你的确定之后的逻辑代码...
});
document.getElementById('test').onclick = function(){
    LjBox.show();
}
