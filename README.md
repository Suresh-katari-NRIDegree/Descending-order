# Descending-order
def descending(arr):
    n = len(arr)

    for i in range(n):
        for j in range(i + 1, n):
            # Compare two elements
            if arr[i] < arr[j]:
                # Swap elements if arr[i] is less than arr[j]
                arr[i], arr[j] = arr[j], arr[i]
    return arr

# Example usage
descending= [10,9,6,0,7,8]
arr=decsendig(arr)
print=("decsending:",arr)
