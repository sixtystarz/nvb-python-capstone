# Bad
def f(x, y):
    return x * 0.3 + y * 0.4

# Good
def weighted_score(quiz_avg, assignment_avg):
    """Calculate weighted course score: quiz 30%, assignment 40%."""
    return quiz_avg * 0.30 + assignment_avg * 0.40
