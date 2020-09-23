<div align="center">

## ^\!Now you can reboot pc from ur program


</div>

### Description

*  Now you can reboot pc from ur program

PLEASE VOTE FOR ME !!! Nitin Jinfal */
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[my name  is Nitin Jindal \(from Panchkula,Haryana\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/my-name-is-nitin-jindal-from-panchkula-haryana.md)
**Level**          |Intermediate
**User Rating**    |4.2 (67 globes from 16 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[System Services/ Functions](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/system-services-functions__3-23.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/my-name-is-nitin-jindal-from-panchkula-haryana-now-you-can-reboot-pc-from-ur-program__3-7588/archive/master.zip)





### Source Code

```
/*  Now you can reboot pc from ur program
   PLEASE VOTE FOR ME !!! Nitin Jinfal */
#include <stdio.h>
#include <dos.h>
#include <conio.h>
main()
{
union REGS i,o;
printf("\nPress any key to REBOOT !!!!");
getch();
int86(0x19,&i,&o);
return 0;
}
```

