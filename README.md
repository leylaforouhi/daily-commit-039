def remove_spaces(tex):
    return text.replace(" ", "")

if __name__ == "__main__":
    sample = "GitHub daily commits"
    print(f"Without spaces: {remove_spaces(sample)}")
