<template>
  <div class="hello">
    <h1></h1>
    <h2 v-if="isNaN(stpob)">Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
          </a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
        >
          Forum
          </a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
        >
          Community Chat
          </a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
        >
          Twitter
          </a>
      </li>
      <br>
      <li>
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
        >
          Docs for This Template
          </a>
      </li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          vue-router
          </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
          </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
          </a>
      </li>
      <li>
        
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
          </a>
      </li>
    </ul>
  </div>
</template>

<script>
import {a} from "@/js/temp.js"
export default {
  name: "HelloWorld",
  data() {
    return {
      stpob:'',
    };
  },
  methods: {
    cc() {
      //  let [a,b,c] = [1,2,3]
      //  console.log(a)
      //  console.log(b)
      //  console.log(c)

      // let [a,b='hhh'] = ['ggg']
      // console.log(a+b,333)

      // let {a,b} = {a:'kkk',b:'uuu'}
      // console.log(a+b,444)

      // let a
      // ({a} = {a:'oooo'})
      // console.log(a)

      // const [a,b,c,e,f,g]="哈啊啊啊"
      // console.log(a)
      // console.log(b)
      // console.log(c)
      // console.log(e)
      // console.log(f)
      // console.log(g)

      // function kyp(...arr){
      //   console.log(arr[0])
      //   console.log(arr[1])
      //   console.log(arr[2])
      //   console.log(arr[3])
      // }
      // kyp(1,2,3);
      // let arr1 = ['rrr','jjj','ppp']
      // let arr2 = [...arr1];
      // console.log(arr2,2)
      // arr2.push('mnb')
      // console.log(arr1,1)

      // function uy(first,...arg){
      //   console.log(arg.length+1)
      // }
      // uy(1,2,3,4,5,6)

      // function pi(first,...arg){
      //   for(let val of arg){
      //     console.log(val)
      //     console.log(first,69)
      //   }
      // }
      // pi(1,2,3,4,5,6)

      // let kb = '大众产品'
      // let blog = `发改运费发给发育${kb}负压给我发佛老`
      // document.write(blog)

      // let a=1
      // let b=4
      // let ky = `${a+b}`
      // document.write(ky)

      // let bus = '呵呵'
      // let gus = '哈哈哈哈哈哈哈呵呵'
      // document.write(gus.indexOf(bus));//indexOf验证里面是否有

      // let bus = '呵呵'
      // let gus = '哈哈哈哈哈哈哈呵呵'
      // document.write(gus.startsWith(bus));startsWith验证是否出现在句首

      // let bus = '呵呵'
      // let gus = '哈哈哈哈哈哈哈呵呵'
      // document.write(gus.endsWith(bus));startsWith验证是否出现在句尾
      // document.write('bus|'.repeat(3));

      // let b = 10/4;
      // console.log(Number.isFinite(b))验证是否是数字
      // console.log(Number.isInteger(b))//验证是否是整数
      //console.log(Number.isNaN(b))//验证是否是特殊字符

      //let c = 9.18;
      //console.log(Number.parseInt(c))//转换成整数
      //console.log(Number.parseFloat(c))//转换成浮点型

      //console.log(Number.MAX_SAFE_INTEGER)最大安全整数
      //console.log(Number.MAX_SAFE_INTEGER)最小安全整数

      //let a = Math.pow(2,53)-1
      //console.log(Number.isSafeInteger(a))//安全整数判断

      // let json = {
      //   '0':'aepex',
      //   '1':'胖子',
      //   '2':'py',
      //   length:3
      // }
      //let arr = Array.from(json);//转换成数组
      //console.log(arr)

      //let arr = Array.of(4,6,8,10,'op')//转换数组
      //console.log(arr)

      //let arr = [1,2,3,4,5,6,7,8,9,] //find数组查找方法value：表示当前查找的值。index：表示当前查找的数组索引。arr：表示当前数组。
      // console.log(arr.find(function(value,index,arr){
      //   return value > 5
      // }))

      // let arr = [1,2,3,4,5,6,7,8,9]
      // arr.fill('bus',3,3)
      // console.log(arr)

      // let arr=[0,1,2,3,4,5,6,7,8,9];  fill第一个参数是填充的变量，第二个是开始填充的位置，第三个是填充到的位置。
      // arr.fill('jspang',2,5);
      // console.log(arr);

      // let arr = ['opl','有点好笑','fgafav']
      // for(let item of arr){ 通过for输出数组内容
      //   console.log(item);
      // }

      // let arr = ['opl','有点好笑','fgafav'] 通过for输出数组索引
      // for(let index of arr.keys()){
      //   console.log(index);
      // }

      // let arr = ['opl','有点好笑','fgafav'] //entries同时输出数组的索引和内容
      // for(let [index,item] of arr.entries()){
      //   console.log(index,item);
      // }

      //   let arr = ['opl','有点好笑','fgafav']entries()实例方式生成的是Iterator形式的数组，
      //   那这种形式的好处就是可以让我们在需要时用next()手动跳转到下一个值
      //   let list = arr.entries();
      //   console.log(list.next().value)
      //   console.log(list.next().value);
      //   console.log(list.next().value);
      //  }

      // function bac(val){//throw new Error抛出错误
      //   if(val==0){
      //     throw new Error('This is error')
      //   }
      //   let b = 1 ;
      //   return val+b
      // }
      // console.log(bac.length)

      //  var add = (a,b=1) => a+b;//箭头函数应用
      //  console.log(add(1))

      //  var pdf = (a,b=1) =>{
      //    console.log("uaygfaffia")
      //    return a+b
      //  }
      //  console.log(pdf(2))

      // let json = {
      //   a:'乐天',
      //   b:'hehe'
      // }
      // function fun(a,b ='wdnmd'){
      //   console.log(a,b)
      // }
      // fun(json)

      // let arr = ['jsk','哈哈','框框']
      // function fun(a,b,c){
      //   console.log(a,b,c)
      // }
      // fun(...arr)

      // let obj = { in是用来判断对象或者数组中是否存在某个值的
      //   a:'jspang',
      //   b:'技术胖'
      // }
      // console.log('a' in obj)

      // let arr = [,,,,,]
      // console.log(arr.length)

      // console.log(0 in arr)
      // let arr2 = ['哈哈','无语']
      // console.log(0 in arr2)

      // let arr = ['fjaf','figafg','uigig'] //forEach
      // arr.forEach((val,index) =>{
      //   console.log(val,index)
      // })

      // let arr = ['fjaf','figafg','uigig']//filter遍历
      // arr.filter(x => console.log(x))

      // let arr = ['fjaf','figafg','uigig']//some遍历
      // arr.some(x=>console.log(x))

      // let arr = ['fjaf','figafg','uigig']//map元素被替换了
      // console.log(arr.map(x=>'web'))

      // let arr = ['fjaf','figafg','uigig']//join拼接
      // console.log(arr.join('/'))

      // let arr = ['fjaf','figafg','uigig']
      // console.log(arr.toString())

      // let mk14 = 'dsyu' //变量声明
      // let hkin = 'wen'
      // var obj = {
      //   mk14,hkin
      // }
      // console.log(obj)

      // let obj = {//对象里的方法
      //   add:function(a,b){
      //     return a+b
      //   }
      // }
      // console.log(obj.add(1,3))

      // console.log(+0 === -0); //true  区分=== 和 is方法的区别是什么   ===为同值相等，is()为严格相等
      // console.log(NaN === NaN); //false
      // console.log(Object.is(+0, -0)); //false
      // console.log(Object.is(NaN, NaN)); //true

      // var a = {a:'iiii'}  //Object.assign合并对象
      // var b = {b:'pppp'}
      // var c = {c:'cccc'}
      // let d = Object.assign(a,b,c)
      // console.log(d)

      // var g = Symbol('pdf')
      // console.log(typeof(g))
      // console.log(g)
      // console.log(g.toString)

      // let arr = {name:"哈哈",pge:"ui"}
      // let age = Symbol()
      // arr[age]=18;
      // for(let item in arr){
      //   console.log(arr[item])
      // }

      // let obj = { name: "jspang", skill: "web" };//使用Symbol来进行循环保护。
      // let age = Symbol();
      // obj[age] = 18;
      // for (let item in obj) {
      //   console.log(obj[item]);
      // }
      // console.log(obj);

      // let o = new Set([1,2,3,4,1])//重复只能出现一个
      // console.log(o)

      // let o = new Set([1,2,3,4,1])//set添加delete删除has查找
      // o.add('哈哈')
      // console.log(o)

      // let setArr = new Set(["jspang", "技术胖", "web", "jspang"]);删除clear:
      // console.log(setArr); //Set {"jspang", "技术胖", "web"}
      // setArr.clear();

      // let setArr = new Set(["jspang", "技术胖", "web", "jspang"])//获取set的大小
      //  for(let item of setArr){
      //    console.log(item)
      //  }
      //  console.log(setArr.size,45)

      // let obj = new WeakSet();//WeakSet的声明
      // let objy = {a:'name',b:'setob'}
      // obj.add(objy);
      // console.log(obj);

      // let json = {
      //   name:'you',
      //   uk:'but'
      // }
      // console.log(json.name);

      // var map = new Map();
      // map.set(json,'iam')
      // console.log(map)
      // console.log(map.get(json))//get获取deletes删除size大小查找是否存在has清楚所有元素clear

      // var por = new Proxy({   //声明Proxy   target：得到的目标值 key：目标的key值，相当于对象的属性
      //   add:function(val){
      //     return val + 10;
      //   },
      //   name:"the is op"
      // },{
      //   get:function(target,key,property){
      //     console.log("ok is non");
      //     return target[key];
      //   },
      //   set:function(target,key,value,receiver){
      //      console.log(`setting ${key} = ${value}`)
      //      return target[key] = value;
      //   }
        
      // });
      // console.log(por.name)
      // por.name = 'js肥'

      // let get = function(){
      //   return 'this of'
      // };
      // var handler = {
      //   apply(target, ctx ,args ){
      //     console.log('do apply');
      //     return Reflect.apply(...arguments);
      //   }
      // }
      // var pro = new Proxy(target,handler);
      // console.log(pro())
      

      // let state = 1;
      // function setop1(re,ty){
      //   console.log(1)
      //   if(state == 1){
      //     re(2)
      //   }else{
      //     ty(3)
      //   }
      // }
      // function setop2(re,ty){
      //   console.log("wdnmd")
      //   if(state == 1){
      //     re("ob")
      //   }else{
      //     ty("textname")
      //   }
      // }
      // function setop3(re,ty){
      //   console.log("hhhhhhh")
      //   if(state == 1){
      //     re("又被搞笑到")
      //   }else{
      //    ty("发给个i哇发u")
      //   }
      // }
      // new Promise(setop1).then(function(val){
      //   console.log(val)
      //   return new Promise(setop2)
      // }).then(function(val){
      //   console.log(val)
      //   return new Promise(setop3)
      
      // }).then(function(val){
      //   console.log(val)
      //   return val
      // })

//       let state=1;       //promise执行多步操作,必须保证上一步完成，才能顺利进行下一步

// function step1(resolve,reject){
//     console.log('1.开始-洗菜做饭');
//     if(state==1){
//         resolve('洗菜做饭--完成');
//     }else{
//         reject('洗菜做饭--出错');
//     }
// }


// function step2(resolve,reject){
//     console.log('2.开始-坐下来吃饭');
//     if(state==1){
//         resolve('坐下来吃饭--完成');
//     }else{
//         reject('坐下来吃饭--出错');
//     }
// }


// function step3(resolve,reject){
//     console.log('3.开始-收拾桌子洗完');
//      if(state==1){
//         resolve('收拾桌子洗完--完成');
//     }else{
//         reject('收拾桌子洗完--出错');
//     }
// }

// new Promise(step1).then(function(val){
//     console.log(val);
//     return new Promise(step2);

// }).then(function(val){
//      console.log(val);
//     return new Promise(step3);
// }).then(function(val){
//     console.log(val);
//     return val;
// });

    // class Coder{  //声明了一个类
    //   name(val){
    //     console.log(val)
    //   }
    //   skill(val){
    //     console.log(this.name('哈哈哈')+':'+'skill:'+val);
    //   }
    //   constructor(a,b){
    //     this.a = a
    //     this.b = b
    //   }
    //   add(){
    //     return this.a+this.b
    //   }
    // }
    // let jsob= new Coder(1,2);
    // // jsob.name("namel")  使用类里面的方法
    // // jsob.skill('ui')
    // console.log(jsob.add())
    

    // class pot extends Coder{  //class继承

    // }
    // let pott = new pot;
    // pott.name('呵呵')

    // console.log(this.a)
    let c = 'kdf';
    if(isNaN(c)){
      console.log(c,11)
    }else{
      console.log(c,22)
    }
     
    }
  },
  created() {
    this.cc();
  },
  mounted() {},
  updated() {},
  directives: {},
  props: [],
  components: {},
  computed: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

