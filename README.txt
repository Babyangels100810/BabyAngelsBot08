# ---- 3 լեզվով ողջույնի տեքստեր ----
WELCOME_TEXTS = {
    "hy": (
        f"🐰🌸 **Բարի գալուստ BabyAngels** 🛍✨\n\n"
        f"💖 Շնորհակալ ենք, որ միացել եք մեր սիրելի ընտանիքին ❤️ Դուք արդեն մեր հատուկ հաճախորդն եք՝ **№{customer_no}** ✨\n"
        f"Մեր նպատակը՝ ամեն այցը դարձնել հաճելի և օգտակար գնումների փորձ։\n\n"
        f"🎁 **Սկսեք հիմա և ստացեք հատուկ նվեր**\n"
        f"Ձեր առաջին պատվերի համար մենք անմիջապես տրամադրում ենք **10% զեղչ** 💝 — "
        f"օգտագործեք և վայելեք առավելագույնը։\n\n"
        f"📦 **Ի՞նչ կգտնեք այստեղ**\n"
        f"• Ժամանակակից և օգտակար ապրանքներ՝ ամեն օր թարմացվող ընտրանիով\n"
        f"• Հատուկ առաջարկներ և բացառիկ զեղչեր միայն մեր Telegram ընտանիքի համար\n"
        f"• Հարմարավետ և արագ առաքում 🚚\n\n"
        f"💱 **Փոխարկումներ՝ արագ և հուսալի**\n"
        f"BabyAngels-ում կարող եք հեշտությամբ կատարել հետևյալ փոխանակումները՝\n"
        f"- **PI ➜ USDT** (թարմ կուրս, +20% սպասարկում)\n"
        f"- **FTN ➜ AMD** (միայն 10% սպասարկում)\n"
        f"- **Alipay լիցքավորում** (1 CNY = 58֏)\n\n"
        f"✨ **Սկսելու համար՝ պարզապես ընտրեք բաժինը ներքևում** 👇"
    ),
    "ru": (
        f"🐰🌸 **Добро пожаловать в BabyAngels** 🛍✨\n\n"
        f"💖 Спасибо, что присоединились к нашей семье! ❤️ Вы уже наш особый клиент — **№{customer_no}** ✨\n"
        f"Наша цель — делать каждое посещение приятным и полезным опытом покупок.\n\n"
        f"🎁 **Начните сейчас и получите подарок**\n"
        f"За первый заказ мы сразу даём **скидку 10%** 💝 — используйте и получайте максимум выгоды.\n\n"
        f"📦 **Что вы найдёте у нас**\n"
        f"• Современные и полезные товары с ежедневно обновляемым ассортиментом\n"
        f"• Специальные предложения и эксклюзивные скидки только для нашего Telegram-сообщества\n"
        f"• Удобная и быстрая доставка 🚚\n\n"
        f"💱 **Обмены — быстро и надёжно**\n"
        f"В BabyAngels вы можете легко выполнить:\n"
        f"- **PI ➜ USDT** (актуальный курс, комиссия +20%)\n"
        f"- **FTN ➜ AMD** (комиссия всего 10%)\n"
        f"- **Пополнение Alipay** (1 CNY = 58֏)\n\n"
        f"✨ **Чтобы начать — выберите раздел ниже** 👇"
    ),
    "en": (
        f"🐰🌸 **Welcome to BabyAngels** 🛍✨\n\n"
        f"💖 Thank you for joining our lovely family! ❤️ You are already our special customer — **No.{customer_no}** ✨\n"
        f"Our goal is to make every visit a pleasant and useful shopping experience.\n\n"
        f"🎁 **Start now and get a special gift**\n"
        f"For your first order we immediately provide a **10% discount** 💝 — enjoy and get the most out of it.\n\n"
        f"📦 **What you’ll find here**\n"
        f"• Modern and useful products with a daily-updated selection\n"
        f"• Special offers and exclusive discounts for our Telegram family\n"
        f"• Convenient and fast delivery 🚚\n\n"
        f"💱 **Exchanges — fast & reliable**\n"
        f"At BabyAngels you can easily make:\n"
        f"- **PI ➜ USDT** (live rate, +20% service)\n"
        f"- **FTN ➜ AMD** (only 10% service)\n"
        f"- **Alipay top-up** (1 CNY = 58֏)\n\n"
        f"✨ **To get started, simply choose a section below** 👇"
    ),
}

# Ընտրիր լեզուն (օրինակ՝ ըստ քո user settings-ի)
user_lang = "hy"  # "ru" կամ "en"
welcome_text = WELCOME_TEXTS.get(user_lang, WELCOME_TEXTS["hy"])

    "help": {
        "hy": "❓ Օգնություն — ընտրեք բաժին կամ գրեք ադմինին։",
        "ru": "❓ Помощь — выберите раздел или напишите администратору.",
        "en": "❓ Help — pick a section or message the admin."
    },
    "error": {
        "hy": "⚠️ Սխալ տեղի ունեցավ, խնդրում ենք փորձել կրկին։",
        "ru": "⚠️ Произошла ошибка, попробуйте ещё раз.",
        "en": "⚠️ Something went wrong, please try again."
    }
}
