import logging
import time

logger = logging.getLogger()
console = logging.StreamHandler()
console.setLevel(logging.INFO)
formatter = logging.Formatter('%(asctime)s %(levelname)s %(message)s')
console.setFormatter(formatter)
logger.addHandler(console)

init()
def printYummyBrownie(msg):
	print(Fore.RESET + "#################")
	timestr = time.strftime('%Y-%m-%d %H:%M:%S')
	print(Fore.GREEN + timestr + msg)
	print(Fore.RESET + "#################")

def printYummyForm(msg):
	print(Fore.RESET + "#################")
	timestr = time.strftime('%Y-%m-%d %H:%M:%S')
	print(Fore.BLACK + timestr + msg)
	print(Fore.RESET + "#################")

def storeBrownie(ua,host, uri, YummyInfo,filename = "WideBrownie.log"):
	msg = "ua: %s\nhost: %s\nuri: %s\n password: %s \n" % (ua, host, uri, YummyInfo)
	storeAtFile(msg, filename)
def storeForm(ua, host, uri, rawbrownie,filename = "WideBrownie.log"):
	msg = "ua: %s\nhost: %s\nuri: %s\n rawbrownie: %s \n" % (ua, host, uri, rawbrownie)
	storeAtFile(msg, filename)
	
def storeAtFile(msg,filename):
	f = open(filename, "a+")
	timestr = time.strftime('%Y-%m-%d %H:%M:%S')
	f.write(timestr + "\n" +msg)
	f.close()
