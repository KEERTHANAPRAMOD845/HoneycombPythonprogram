def print_hexagon_shell():
    print("  ___  ")
    print(" /   \\ ")
    print(" \\___/ ")

def print_honeycomb(rows, cols):
    for i in range(rows):
            print_hexagon_shell()
    if i% 2 == 0:
            print("" * (rows - i - 1) + "" * cols)
    else:
            print("" * (rows - i - 1) + "" * cols)

rows = int(input("Enter the row:"))
cols = int(input("Enter the cols:"))
print_honeycomb(rows, cols)
