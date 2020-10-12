# 30-days-of-HackerRank
Python solutions

#DAY 2
# Complete the solve function below.
def solve(meal_cost, tip_percent, tax_percent):
    meal=meal_cost
    tip= meal_cost*tip_percent/100
    tax= meal_cost*tax_percent/100
    #print(meal_cost*tip_percent/100+ meal_cost*tax_percent/100)
    total =round(meal+tip+tax)
    print (total)
  
if __name__ == '__main__':
    meal_cost = float(input())

    tip_percent = int(input())

    tax_percent = int(input())

    solve(meal_cost, tip_percent, tax_percent)
 #DAY 3
