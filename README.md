# vue-calendar-datepikcer

## Install

```js
  npm install vue-calendar-datepicker
```
## Usage

```js
  import Calendar from 'vue-calendar-datepikcer';
	export default{
	    components:{
		 	    Calendar,
	 	  },
      data(){
          return{
				      calendar:{
		              display:'',
		              show:false,
		              range:true,
		              zero:true,
		              begin:[],
		              value:[], //默认日期
		              lunar:false, //显示农历
		              events:{},
		              select:(begin,end)=>{
		            	    //关闭选择器后的回调
		              }
		            },          
          }
      }
  }
```
