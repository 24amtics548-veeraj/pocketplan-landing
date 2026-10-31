# PocketPlan – Responsive Product Landing Page (UI/UX using Figma, IPS)

**Enrollment No:** 202403103510548
**Name:** Waghela Veeraj


## 1. Product and target users
**PocketPlan** is a fictional budgeting app for students and first-time earners. It splits monthly pocket money into a daily spending limit and updates it after every expense.

**Target users:** college students (18–24) living in hostels or commuting, who get a fixed monthly amount and often run out before the month ends. They use phones all day, so the app and page must be fast and simple.
**Main job of the page:** make the visitor understand the value in one interaction and click "Start free".

## 2. Design choices
- **One interactive moment:** the pocket-money slider in the hero shows the daily limit instantly. Visitors see the product benefit before signing up.
- **Phone mockup** shows the core feature (daily limit ring + recent expenses), so the product is clear without extra text.
- **Colors:** deep plum for trust and calm, coral only for action buttons and key numbers, soft lilac and sky blue for friendly section backgrounds.
- **Typography:** Sora for headings (modern, rounded), Manrope for body (very readable on mobile). 6 text styles only.
- **Spacing and shape:** 8-point spacing; large radius (14 for buttons, 28 for cards) for a friendly feel.
- **Copy:** plain words, active verbs, one idea per card.
- **Responsive and accessible:** cards stack to one column on mobile, visible keyboard focus, reduced-motion respected, strong text contrast.

## 3. Colour styles (Figma → Local styles)
| Style name | Hex | Use |
|---|---|---|
| Plum/900 | #2D1B4E | Headings, phone, dark card |
| Plum/700 | #4A3175 | Body text on light |
| Coral/500 | #FF6B57 | Primary buttons, key numbers |
| Sky/200 | #BFE3FF | Accent sections |
| Lilac/100 | #EDE7FA | Hero and card backgrounds |
| Ink/900 | #1A1230 | Footer |
| White | #FFFFFF | Page, buttons text |

## 4. Text styles
| Style | Font | Weight | Size / Line |
|---|---|---|---|
| Display/H1 | Sora | Bold | 56 / 62 |
| Display/H2 | Sora | Bold | 36 / 44 |
| Heading/H3 | Sora | SemiBold | 20 / 28 |
| Body/Large | Manrope | Medium | 18 / 28 |
| Body/Regular | Manrope | Medium | 16 / 24 |
| Button | Manrope | ExtraBold | 16 / 20 |

## 5. Reusable components (5)
1. **Button** – variants Primary (coral) / Secondary (outline), size Default / Small. Auto Layout horizontal, padding 16/28, radius 14.
2. **Header** – logo, 4 links, Button/Small. Auto Layout horizontal, space-between, height 76.
3. **Feature Card** – icon tile, H3, body. Auto Layout vertical, padding 32, gap 16, radius 28. Variants: Lilac / Sky / Plum background.
4. **Transaction Row** – label + amount, space-between, padding 12 vertical. Used 3 times in the phone.
5. **Slider Card** – label + value, slider, result text. Auto Layout vertical, padding 24, radius 20.

> Figma link: https://www.figma.com/design/SosdiVTtEmnVT3mPwENpMe/pocketplan-landing?node-id=1-2&t=RqWJE2HXw7M0k0O2-1