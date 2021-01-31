#include <stdio.h>

int main(void)
{
    int order, existing_inventory, remaining_inventory, price;
    double take;
    order = 3;
    price = 10000
    existing_inventory = 5;
    remaining_inventory = existing_inventory - order;
    take = (order * price)* 1.1;
    
    printf("주문건수 : %d건 \n", order);
    printf("기존 재고량 : %d개 \n", existing_inventory);
    printf("남은 재고량 : %d개 \n", remaining_inventory);
    printf("매출액(부가세포함) : %f원\n", take);
    
    return 0;
}
