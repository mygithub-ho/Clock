




#形状
  》矩形:
    ctx.fillRect() 填充矩形
    ctx.strokeRect() 框线矩形

  》圆
    ctx.arc()  圆
    ctx.arcTo() 圆弧

  》线
   ctx.beginPath()  开始一个路径
   ctx.moveTo()     移动画笔到某点
   ctx.lineTo()     让路径中拥有(并不会直接绘制)一条到某点的线
   ctx.rect()      让路径中拥有(并不会直接绘制)一个矩形
   ctx.fill()       填充当前路径
   ctx.stroke()     描边当前路径
   ctx.closePath()  结束一个路径
   ctx.strokeStyle()  改变颜色

  从画布中清除矩形区域
  画布的特点:画布上的元素
    ctx.clearRect()   
   
  var now = new get

  》曲线
   ctx.quadraticCurveTo(cp1x,cp1y,x,y) 二次贝塞尔 
   ctx.bezierCurveTo(cp1x,cp1y,cp2x,cpxy,x,y) 三次贝塞尔
  
  》位移和变形(挪动画布)
     只保存画布(包含画笔)状态 不保存任何图像
       ctx.save(); 保存画布
       ctx.restore(); 复原画布
       ctx.translate(x,y); 位移整个画布
       ctx.rotate((Math.PI/180)*6);  旋转
       ctx.scale()

   >样式
   ctx.fillStyle = '#232443'
   ctx.strokeStyle = '#243442'

   ctx.width()
   ctx.height()

 引入图片
  <img src="" alt="">
   window.onload = function(){
   var img = socument.querySelector('#img');
   var xxx = ctx.createPattern(img,'no-repate');
   ctx.fillStyle = xxx;
  }

    var img = new Image()




 // document.onclick = function(){
    //  // ctx.clearRect(0,0,600,600)
    //  ctx.width = ctx.height = 600;
    //  ctx.clearRect(0,0,600,600)
    // }


