# AutoFixGeorgia — ავტოსერვისის ვებსაიტი

მზიურის ვებ-დეველოპმენტის კურსის ფინალური პროექტი.

**AutoFixGeorgia** არის  ხუთგვერდიანი ვებსაიტი გამოგონილი
ავტოსერვისისთვის. დიზაინი შთაგონებულია კლასიკური ავტოსერვისის საიტებით და
მთლიანად ნულიდანაა აწყობილი — საკუთარი SCSS არქიტექტურით, Bootstrap-ის
ბადითა და კომპონენტებით.

(Car Repair - Auto Repair Service Website Template#51928) - ინსპირაციისთვის გამოყენებული Template.
(https://demo.templatemonster.com/demo/51928.html?_gl=1*3d6515*_ga*MjAzMjcwMDgwNS4xNzg2MzU5MjY5*_ga_FTPYEGT5LY*czE3ODg0MjMyMjYkbzEzJGcxJHQxNzg4NDIzMjI3JGo1OSRsMCRoMjUwNDc4MDkx)

## გვერდები

|---|---|---|
| მთავარი | `index.html` | Hero-სლაიდერი, სარეკლამო ბლოკები, პოპულარული სერვისები, შეფასებები |
| ჩვენ შესახებ | `about.html` | კომპანიის ისტორია სტატისტიკით, მუშაობის ეტაპები |
| სერვისები | `services.html` | 6 სერვისის ბარათი ფასებით |
| სიახლეები | `news.html` | მთავარი სიახლე და სიახლეების ბადე |
| კონტაქტი | `contact.html` | საკონტაქტო ბარათები |

## გამოყენებული ტექნოლოგიები

- **HTML5** — (`header`, `nav`, `section`, `footer`)
- **CSS3 / SCSS** — ცვლადები, nesting, მიქსინები, `@include`, 11 partial ფაილი
- **Bootstrap 5.2** — Grid სისტემა, Navbar, Carousel, Card, Accordion, Form
- **Bootstrap Icons** — ინტერფეისის აიქონები
- **Media Queries** — საკუთარი breakpoint-ები: 992px / 768px / 480px


## პროექტის სტრუქტურა

```
final_project/
├── index.html
├── about.html
├── services.html
├── news.html
├── contact.html
├── css/
│   └── style.css        (SCSS-დან დაკომპილირებული)
├── scss/
│   ├── _variables.scss  (ფერები, ფონტები, ზომები)
│   ├── _mixins.scss     (ღილაკის მიქსინი)
│   ├── _global.scss     (საერთო სტილები)
│   ├── _header.scss
│   ├── _footer.scss
│   ├── _home.scss
│   ├── _about.scss
│   ├── _services.scss
│   ├── _news.scss
│   ├── _contact.scss
│   ├── _responsive.scss (საკუთარი media query-ები)
│   └── style.scss       (partial-ების გამაერთიანებელი)
├── images/
└── README.md
```


## წყაროები

- ფოტოები: უფასო სურათები [Pexels](https://www.pexels.com)-იდან
- აიქონები: [Bootstrap Icons](https://icons.getbootstrap.com)

## ავტორი

**ლევან ქაჯაია (Levan Kajaia)**
