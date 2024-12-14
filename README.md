# python-intern-task

# task to find second largest number
def find_second_largest(numbers):
    
    unique_numbers = list(set(numbers))

    unique_numbers.sort(reverse=True)

    return unique_numbers[1]

numbers = [10, 20, 4, 45, 99]
second_largest = find_second_largest(numbers)
print("The second largest number is:", second_largest)
