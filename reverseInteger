class Solution(object):
    def reverse(self, x):
        """
        :type x: int
        :rtype: int
        """
        self = 0
        l = len(str(x))
        while (l>0):
            l += -1
            self += (x%10)*10**l
            x = int(x/10)
        return self

def stringToInt(input):
    return int(input)

def intToString(input):
    if input is None:
        input = 0
    return str(input)

def main():
    import sys
    def readlines():
        for line in sys.stdin:
            yield line.strip('\n')
    lines = readlines()
    while True:
        try:
            line = lines.next()
            x = stringToInt(line)
            
            ret = Solution().reverse(x)

            out = intToString(ret)
            print out
        except StopIteration:
            break

if __name__ == '__main__':
    main()
