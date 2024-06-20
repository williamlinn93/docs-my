# vuejs.org မြန်မာ

## ပါ၀င်ကူညီခြင်း

ဒီဆိုက်ကို [VitePress](https://github.com/vuejs/vitepress) ဖြင့် တည်ဆောက်ထားပြီး [@vue/theme](https://github.com/vuejs/vue-theme) ဖြင့် ဒီဇိုင်းဆင်ထားပါတယ်။ ဆိုက်တွင်ပါ၀င်သောအကြာင်းအရာများကို Markdown ဖော်မတ်ဖြင့် ရေးသားထားပြီး `src` ထဲတွင် ထားရှိပါတယ်။ ရိုးရှင်းသော ပြုပြင်မွမ်းမံမှုများအတွက်၊ သင်ဟာ GitHub ပေါ်မှာဘဲ တိုက်ရိုက်ပြင်ဆင်နိုင်ပြီး တစ်ခါတည်း Pull Request လုပ်နိုင်ပါတယ်။

ဒီဆိုက်ကို Localမှာ တည်ဆောက်မယ်ဆိုရင်၊ Package Manager အဖြစ် [pnpm](https://pnpm.io/) ကို သုံးစေချင်ပါတယ်။

```bash
pnpm i
pnpm run dev
```

ဒီပရောဂျက်က Node.js ဗားရှင်း `v18` နဲ့အထက်လိုအပ်ပါတယ်။ ပြီးတော့ corepack ကိုလည်း enable လုပ်ထားဖို့ အကြံပြုပါတယ်။

```bash
corepack enable
```

## Content ပြုပြင်ခြင်း

- [ရေးလို့ရတဲ့ Markdown ဖိုင်](https://vitepress.dev/guide/markdown)အကြောင်းတွေနဲ့ [markdownဖိုင်မှာ Vue syntax ရေးနည်း](https://vitepress.dev/guide/using-vue) တွေကိုတော့ VitePressရဲ့ docsတွေမှာကြည့်ပါ။

- စာရေးသားခြင်းနဲ့ ပတ်သက်တဲ့ စည်းမျဉ်းများ၊ အကြံပြုချက်များနဲ့ documentation အကြောင်းအရာ ထိန်းသိမ်းခြင်းများအတွက် [စာရေးသားနည်း ဂိုက်လိုင်းများ](https://github.com/vuejs/docs/blob/main/.github/contributing/writing-guide.md) မှာ ကြည့်ပေးပါ။

## theme ပြုပြင်ခြင်း

- Theme မှာ ပြုပြင်စရာတွေရှိရင်တော့ [documentation နဲ့အတူတကွလုပ်ဆောင်နိုင်တဲ့ theme ရေးရန် လမ်းညွှန်ချက်များ](https://github.com/vuejs/vue-theme#developing-with-real-content) မှာ ကြည့်ပေးပါ။
