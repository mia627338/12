import random

def generate_random_list(length, min_value, max_value):
    random_list = [random.randint(min_value, max_value) for _ in range(length)]
    return random_list

def find_max(input_list):
    max_value = max(input_list)
    return max_value

def find_min(input_list):
    min_value = min(input_list)
    return min_value

length = 10
min_value = 1
max_value = 100

random_list = generate_random_list(length, min_value, max_value)
print("随机生成的列表：", random_list)

max_value = find_max(random_list)
print("列表中的最大值：", max_value)

min_value = find_min(random_list)
print("列表中的最小值：", min_value)
