deploy是2024.1.12日创建用于在colab上部署chatglm
如果在colab上遇到有关‘utf-8’的错误可以增加如下指令
import locale
def getpreferredencoding(do_setlocale = True):
    return "UTF-8"
locale.getpreferredencoding = getpreferredencoding
