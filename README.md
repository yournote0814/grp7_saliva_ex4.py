# grp7_saliva_ex4.py
SALIVA, RYAN 
def check_condition(num):
    return num > 15

def print_collection(collection):
    print(collection)

def print_elements_with_types(collection):
    for element in collection:
        print(element, type(element))

# Test the condition
print("18 > 15:", check_condition(18))
print("12 > 15:", check_condition(12))

# Create collections
my_list = ["programming", 37, False]
my_tuple = ("hiking", 28, True)
my_set = {"gaming", 15, False}
my_dict = {"favorite_color": "saliva", "age": 23, "is_student": True}

# Print collections
print_collection(my_list)
print_collection(my_tuple)
print_collection(my_set)
print_collection(my_dict)

# Print elements with types
print_elements_with_types(my_list)
print_elements_with_types(my_tuple)
print_elements_with_types(my_set)
print_elements_with_types(my_dict)
