# vue-calendar-datepikcer

## Install

```js
  npm install vue-calendar-datepicker
```
## Usage

```js
import Calendar from 'vue-calendar-datepikcer';
<script>
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
</script>
```
### Props

- :value Array default:[] * default value for calendar
- :begin Array default:[] * limit begin select date
- :end Array default:[] * limit end select date
- :range Bool default:false * You can select a time period
- :zero Bool default:false * Date zero
- :lunar Bool default:false * Show Chinese Lunar
- :weeks Array * According to the system language changes or custom
- :months Array * According to the system language changes or custom
- :events Object * Customize calendar events

### Features
- You can limit the start and end dates.
- Customize week and month headlines.
- Support show Chinese lunar calendar, Chinese festivals, international festivals
- Support for custom presentation.
- Support multiple choice
- Customize calendar events
