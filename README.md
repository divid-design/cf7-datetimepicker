# WordPress Plugin Contact Form 7 Date and Time picker 
cf7-datetimepicker

Плагин выбора времени и даты для Contact Form 7.

jQuery settings are saved in function "add_datetimepicker()"

Plugin have settings by default:

 $.datetimepicker.setLocale('ru');
        $('#datetimepicker').datetimepicker({
         timepicker:true,
         format:'d.m.Y H:i',
         minDate:0,
         defaultDate:new Date(),
         allowTimes:[
          '11:00',
          '12:00',
          '13:00',
          '14:00',
          '15:00',
          '16:00',
          '17:00',
          '18:00',
          '19:00',
          '20:00',
          '21:00',
          '22:00'
          ]
        });
        
For change the settings, your can use Documentation: https://xdsoft.net/jqplugins/datetimepicker/        
