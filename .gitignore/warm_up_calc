
def rounding_to_kgs(weight):

    return (weight//2.5)*2.5

def choosing_opener(weight, option):

    if weight > 20:
        if option == 'easy':
            opener = rounding_to_kgs(weight*0.9)
        elif option == 'medium':
            opener = rounding_to_kgs(weight*0.93)
        elif option == 'hard':
            opener = rounding_to_kgs(weight*0.95)

        return opener

    else:
        print('Error')


def warm_up_weights(opener):

    warm_ups = []

    if opener <= 20:
        print('Error')
    elif opener < 30:
        warm_ups.append(20.0)
    elif opener < 32.5:
        warm_ups.append(20.0)
        warm_ups.append(25.0)
    elif opener == 35:
        warm_ups.append(20.0)
        warm_ups.append(25.0)
        warm_ups.append(30.0)
    elif opener < 52.5:
        warm_ups.append(20.0)
        warm_ups.append(rounding_to_kgs(opener * 0.67))
        warm_ups.append(rounding_to_kgs(opener * 0.8))
        warm_ups.append(rounding_to_kgs(opener * 0.92))
    elif opener < 150:
        warm_ups.append(20.0)
        warm_ups.append(rounding_to_kgs(opener * 0.55))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.82))
        warm_ups.append(rounding_to_kgs(opener * 0.92))
    elif opener < 190:
        warm_ups.append(20.0)
        warm_ups.append(60.0)
        warm_ups.append(rounding_to_kgs(opener * 0.57))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.8))
        warm_ups.append(rounding_to_kgs(opener * 0.92))
    elif opener < 250:
        warm_ups.append(20.0)
        warm_ups.append(70.0)
        warm_ups.append(rounding_to_kgs(opener * 0.53))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.82))
        warm_ups.append(rounding_to_kgs(opener * 0.93))
    elif opener < 300:
        warm_ups.append(20.0)
        warm_ups.append(70.0)
        warm_ups.append(120.0)
        warm_ups.append(rounding_to_kgs(opener * 0.57))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.82))
        warm_ups.append(rounding_to_kgs(opener * 0.93))
    else:
        warm_ups.append(20.0)
        warm_ups.append(70.0)
        warm_ups.append(120.0)
        warm_ups.append(170.0)
        warm_ups.append(rounding_to_kgs(opener * 0.65))
        warm_ups.append(rounding_to_kgs(opener * 0.75))
        warm_ups.append(rounding_to_kgs(opener * 0.85))
        warm_ups.append(rounding_to_kgs(opener * 0.93))
    return warm_ups

def reps_squat(opener):

    reps = []
    sets = []

    if opener <= 20:
        print('Error')
    elif opener < 30:
        reps.append('x5-7')
    elif opener < 32.5:
        reps.append('x5-7')
        reps.append('x3')
    elif opener == 35:
        reps.append('x5-7')
        reps.append('x3')
        reps.append('x1')
    elif opener < 52.5:
        reps.append('x5-7')
        reps.append('x3')
        reps.append('x1')
        reps.append('x1')
    elif opener < 150:
        reps.append('x8')
        sets.append('x2')
        reps.append('x3-5')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 190:
        reps.append('x8')
        sets.append('x2')
        reps.append('x5')
        sets.append('x2')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 250:
        reps.append('x8')
        sets.append('x2')
        reps.append('x5')
        sets.append('x2')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 300:
        reps.append('x8')
        sets.append('x2')
        reps.append('x6')
        sets.append('x2')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    else:
        reps.append('x8')
        sets.append('x2')
        reps.append('x6')
        sets.append('x2')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    return reps, sets

def reps_bench(opener):

    reps = []
    sets = []

    if opener <= 20:
        print('Error')
    elif opener < 30:
        reps.append('x5-7')
    elif opener < 32.5:
        reps.append('x5-7')
        reps.append('x3')
    elif opener == 35:
        reps.append('x5-7')
        reps.append('x3')
        reps.append('x1')
    elif opener < 52.5:
        reps.append('x5-7')
        reps.append('x3')
        reps.append('x1')
        reps.append('x1')
    elif opener < 150:
        reps.append('x8')
        sets.append('x2')
        reps.append('x5')
        sets.append('x2')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 190:
        reps.append('x8')
        sets.append('x2')
        reps.append('x5')
        sets.append('x2')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 250:
        reps.append('x8')
        sets.append('x2')
        reps.append('x6')
        sets.append('x2')
        reps.append('x5')
        sets.append('x1')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 300:
        reps.append('x8')
        sets.append('x2')
        reps.append('x6')
        sets.append('x2')
        reps.append('x5')
        sets.append('x1')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    else:
        reps.append('x8')
        sets.append('x2')
        reps.append('x6')
        sets.append('x2')
        reps.append('x5')
        sets.append('x2')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    return reps, sets

def warm_up_weights_deadlift(opener):

    warm_ups = []

    if opener <= 20:
        print('Error')
    elif opener < 30:
        warm_ups.append(20.0)
    elif opener < 32.5:
        warm_ups.append(20.0)
        warm_ups.append(25.0)
    elif opener == 35:
        warm_ups.append(20.0)
        warm_ups.append(25.0)
        warm_ups.append(30.0)
    elif opener < 52.5:
        warm_ups.append(rounding_to_kgs(opener * 0.67))
        warm_ups.append(rounding_to_kgs(opener * 0.8))
        warm_ups.append(rounding_to_kgs(opener * 0.92))
    elif opener < 150:
        warm_ups.append(rounding_to_kgs(opener * 0.55))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.82))
        warm_ups.append(rounding_to_kgs(opener * 0.92))
    elif opener < 190:
        warm_ups.append(60.0)
        warm_ups.append(rounding_to_kgs(opener * 0.57))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.8))
        warm_ups.append(rounding_to_kgs(opener * 0.92))
    elif opener < 250:
        warm_ups.append(70.0)
        warm_ups.append(rounding_to_kgs(opener * 0.53))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.82))
        warm_ups.append(rounding_to_kgs(opener * 0.93))
    elif opener < 300:
        warm_ups.append(70.0)
        warm_ups.append(120.0)
        warm_ups.append(rounding_to_kgs(opener * 0.57))
        warm_ups.append(rounding_to_kgs(opener * 0.7))
        warm_ups.append(rounding_to_kgs(opener * 0.82))
        warm_ups.append(rounding_to_kgs(opener * 0.93))
    else:
        warm_ups.append(70.0)
        warm_ups.append(120.0)
        warm_ups.append(170.0)
        warm_ups.append(rounding_to_kgs(opener * 0.65))
        warm_ups.append(rounding_to_kgs(opener * 0.75))
        warm_ups.append(rounding_to_kgs(opener * 0.85))
        warm_ups.append(rounding_to_kgs(opener * 0.93))
    return warm_ups

def reps_deadlift(opener):

    reps = []
    sets = []

    if opener <= 20:
        print('Error')
    elif opener < 30:
        reps.append('x4')
    elif opener < 32.5:
        reps.append('x4')
        reps.append('x2')
    elif opener == 35:
        reps.append('x4')
        reps.append('x2')
        reps.append('x1')
    elif opener < 52.5:
        reps.append('x4')
        reps.append('x2')
        reps.append('x1')
        reps.append('x1')
    elif opener < 150:
        reps.append('x4')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 190:
        reps.append('x5')
        sets.append('x2')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 250:
        reps.append('x5')
        sets.append('x2')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    elif opener < 300:
        reps.append('x6')
        sets.append('x2')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    else:
        reps.append('x6')
        sets.append('x2')
        reps.append('x4')
        sets.append('x1')
        reps.append('x3')
        sets.append('x1')
        reps.append('x2')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
        reps.append('x1')
        sets.append('x1')
    return reps, sets


def print_calculations(warm_ups, reps, sets):

    for a in range(0, len(reps)):
        print(warm_ups[a], reps[a], sets[a])


squat_max = input('Enter squat max: ')
bench_max = input('Enter bench max: ')
dead_max = input('Enter dead max: ')
opener_difficulty = input('Enter how difficult your opener should be (easy, medium, hard): ')

squat_opener = choosing_opener(float(squat_max), opener_difficulty)
bench_opener = choosing_opener(float(bench_max), opener_difficulty)
dead_opener = choosing_opener(float(dead_max), opener_difficulty)

reps_sq, sets_sq = reps_squat(squat_opener)
print('Squat warm-up')
print_calculations(warm_up_weights(squat_opener), reps_sq, sets_sq)
print('Squat opener: ', float(squat_opener))

reps_bp, sets_bp = reps_bench(bench_opener)
print('Bench warm-up')
print_calculations(warm_up_weights(bench_opener), reps_bp, sets_bp)
print('Bench opener: ', float(bench_opener))

reps_dl, sets_dl = reps_deadlift(dead_opener)
print('Deadlift warm-up')
print_calculations(warm_up_weights_deadlift(dead_opener), reps_dl, sets_dl)
print('Deadlift opener: ', float(dead_opener))
