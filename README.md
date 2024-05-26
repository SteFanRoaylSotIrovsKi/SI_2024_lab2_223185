# SI_2024_lab2_223185

## Stefan Sotirovski 223185

### Control Flow Graph

![CFG drawio (1)](https://github.com/SteFanRoaylSotIrovsKi/SI_2024_lab2_223185/assets/166416103/852ea3fc-4078-4903-bf88-8f2be79870da)


### Цикломатската комплексност
Цикломатската комплексност е 10, бидејќи бројот на предикати јазли во кодот е 9 и според формулата P+1, каде што P=9 го добиваме резулатот 10.

### Every statement
1. Ако allItems е null фрла исклучок. Добиваме порака "allItems list can't be null!". 
2. Кога имаме баркод со вредност null, добиваме исклучок RuntimeException("No barcode!")
3. Кога имаме баркод со некоја вредност, но содржи некој знак што не е валиден, добиваме порака "Invalid character in item barcode!"
4. Доколку имаме повеќе

### Multiple Condition
-(price=5000, barcode="0274" discount=0.20)=True & True & True=True
-(price=5000, barcode="2274" discount=0.20)=True & True & False=False
-(price=5000, barcode="2274" discount=-1)=True & False & False(not relevent)=False
-(price=300, barcode="2274" discount=-1)=False & False(not relevent) & False(not relevent)=False
