# GitCourse
Quick git course
graph TD
    A([بداية - Start]) --> B[/إدخال عدد مكون من 5 خانات/]
    B --> C[تعيين قيمة القاسم: Divisor = 10000]
    C --> D[تعيين عداد الحلقة: Counter = 1]
    
    D --> E{هل العداد <= 5؟}
    
    E -- نعم --> F[استخراج الرقم: Digit = Number // Divisor]
    F --> G[/طباعة الرقم Digit/]
    G --> H[تحديث العدد: Number = Number % Divisor]
    H --> I[تحديث القاسم: Divisor = Divisor // 10]
    I --> J[زيادة العداد: Counter = Counter + 1]
    J --> E
    
    E -- لا --> K([نهاية - End])
