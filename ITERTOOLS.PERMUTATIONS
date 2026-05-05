n,m = tuple(map(int, input().split(" ")))
n_arr = list(map(int, input().split(" ")))
m_a_arr = set(map(int, input().split(" ")))
m_b_arr = set(map(int, input().split(" ")))

happyness = 0
for i in n_arr:
    happyness+= (i in m_a_arr) - (i in m_b_arr)

print(happyness)
