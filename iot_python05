# หาพื้นที่สีเหลี่ยม และสามเหลี่ยม โดยรับกว้าง ยาว/ฐาน สูง ทางแป้นพิมพ์ และแสดงผลทางหน้าจอ
# feature การทำงานอะไรบ้าง
# 1. รับค่า กว้าง ยาว
# 2. รับค่า ฐาน สูง
# 3. คำนวณพื้นที่สี่เหลี่ยม และแสดงผล
# 4. คำนวณพื้นที่สามเหลี่ยม และแสดงผล

def inputWidthlenght ( ) :
    wide = float(input('ป้อนความกว้าง : ' ))
    long = float(input('ป้อนความยาว : '))
    return wide,long

def inputBaseHeight ( ):
    base = float(input('ป้อนความยาวฐาน : '))
    high = float(input('ป้อนความสูง : '))
    return base,high

def CalAndShowAreaSquare (wide,long) :
    area = wide*long
    print(f'สี่เหลี่ยมกว้าง {wide} ยาว {long} มีพื้นที่ {area}')
    
def CalAndShowAreaTriangle (base,high) :
    area = base*high/2
    print(f'สี่เหลี่ยมกว้าง {base} ยาว {high} มีพื้นที่ {area}')
    
Wide,Long = inputWidthlenght()
CalAndShowAreaSquare(Wide,Long)
print('------------------------------------------')
Base,High = inputBaseHeight()
CalAndShowAreaTriangle(Base,High)