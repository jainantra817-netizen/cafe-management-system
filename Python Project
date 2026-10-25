
print("===== CAFE MANAGEMENT SYSTEM =====")

print("\nMENU")
print("1. Coffee - Rs.80")
print("2. Burger - Rs.120")
print("3. Sandwich - Rs.90")

print("\nCOMBO OFFERS")
print("4. Coffee + Sandwich - Rs.150")
print("5. Burger + Cold Drink - Rs.130")

total = 0
combo_count = 0

while True:
    choice = int(input("\nEnter your choice (0 to finish): "))

    if choice == 0:
        break

    if choice == 1:
        total = total + 80
        print("Coffee added!")

    elif choice == 2:
        total = total + 120
        print("Burger added!")

    elif choice == 3:
        total = total + 90
        print("Sandwich added!")

    elif choice == 4 or choice == 5:
        if combo_count < 2:
            if choice == 4:
                total = total + 150
                print("Coffee + Sandwich combo added!")
            else:
                total = total + 130
                print("Burger + Cold Drink combo added!")

            combo_count = combo_count + 1
            print("Combos ordered:", combo_count, "/ 2")
        else:
            print("Sorry! Maximum 2 combos allowed.")

    else:
        print("Invalid choice!")

print("\n======= FINAL BILL =======")
print("Total Amount: Rs.", total)
print("Thank you! Visit again.")
