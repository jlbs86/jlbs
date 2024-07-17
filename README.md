#!/usr/bin/python

class JoseBecerril:

    def __init__(self):
        self.name = "Jose Becerril"
        self.entrepreneur = True
        self.developer = True
        self.researcher = True
        self.languages = ["en_US", "es_MX"]

    def say_hi(self):
        print("I'm glad you read my intro! Please also visit my website www.acegdl.com")


me = JoseBecerril()
me.say_hi()
