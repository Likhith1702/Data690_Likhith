def addition(x, y):
    if type(x) == "str" and type(y) == "str":
        if x.isnumeric() and y.isnumeric():
            return int(x) + int(y)
        else:
            raise ValueError('The Input must be numeric')
    else:
        return x + y


def subtraction(x, y):
    return x-y
