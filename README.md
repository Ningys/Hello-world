# Hello-world
just my first testing life

class hello_world(object):
    def __init__(self,name):
        self.name=name
        self.said='nice too meet you!'
        self.__say='say hello'
    def hi_world(self):
        return self.__say
hi=hello_world('Ning')
print hi.hi_world()
print hi.name+','+hi.said
