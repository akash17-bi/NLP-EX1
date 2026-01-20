import re
def detect_word_pattern(pattern, text):
    matches = re.findall(pattern, text)
    if matches:
        print("Word patterns detected:")
        for match in matches:
            print(match)
    else:
        print("No word patterns detected.")
sample_inputs = [
    (r"\b\w{4}\b", "This text has some four word size like test and code"),
    (r"\b[A-Z][a-z]+\b", "India is My Country"),
    (r"\d+", "There are 25 students in class 10"),
    (r"\bpython\b", "I love python programming"),
    (r"\bcat\b", "Dogs are friendly animals")
]
for pattern, text in sample_inputs:
    print("Pattern:", pattern)
    print("Text:", text)
    detect_word_pattern(pattern, text)
    print("-" * 40)
