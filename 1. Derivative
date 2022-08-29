def forward_diff(f, x, h = 0.0001) :
    df = (f(x+h) -  f(x)) / h
    return df

def fx(x) :
    y = pow(x,2)+3*x+5
    print(f'y where x is {x} = {y}')
    return y

x = float(input('input num : '))
df = forward_diff(fx, x)
print('first derivative = ', df)
