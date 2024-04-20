# gold-and-silver
class Gold:
    def __init__(self, weight_grams, purity):
        self.weight_grams = weight_grams
        self.purity = purity

    def display_info(self):
        print("Gold Information:")
        print(f"Weight: {self.weight_grams} grams")
        print(f"Purity: {self.purity}%")

class Silver:
    def __init__(self, weight_grams, purity):
        self.weight_grams = weight_grams
        self.purity = purity

    def display_info(self):
        print("Silver Information:")
        print(f"Weight: {self.weight_grams} grams")
        print(f"Purity: {self.purity}%")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Gold class
    gold_sample = Gold(weight_grams=50, purity=99)

    # Displaying information about the gold
    gold_sample.display_info()

    # Creating an instance of the Silver class
    silver_sample = Silver(weight_grams=100, purity=92)

    # Displaying information about the silver
    silver_sample.display_info()
