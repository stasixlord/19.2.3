import pytest
from app.mycalc import Calculator

class TestCalc:
    def setup(self):
        self.calc = Calculator

    def test_multiply_calc_corr(self):
        assert self.calc.multiply(self, 2, 2) == 4

    def test_division_calc_corr(self):
        assert self.calc.division(self, 6, 2) == 3

    def test_subtraction_calc_corr(self):
        assert self.calc.subtraction(self, 8, 3) == 5

    def test_adding_calc_corr(self):
        assert self.calc.adding(self, 2, 5) == 7
