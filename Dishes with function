import random

dishes_string = 'steak, pasta, pasta, water, salad, bread, water, red wine, white wine'
dish_list = []

for dish in dishes_string.split(','):
    dish_list.append(dish.strip())

unique_dishes = set(dish_list)

def calc_time():
    return random.randint(0, 60)

for dishes in unique_dishes:
    print(dishes.ljust(15, '.'), calc_time(), 'minutes')
