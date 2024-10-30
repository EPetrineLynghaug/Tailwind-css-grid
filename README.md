# # Lecture notes, Tailwind-css-grid

## Tailwind CSS Cheatsheet

En kort oversikt over noen viktige Tailwind CSS-klasser.

| **Kategori**      | **Klasse**                                   | **Beskrivelse**                                                                                       |
|-------------------|----------------------------------------------|-------------------------------------------------------------------------------------------------------|
| **📐 Layout**     | `container`                                  | Sentrerer innholdet, setter bredde basert på skjermstørrelse.                                         |
|                   | `block`                                      | Blokkelement.                                                                                         |
|                   | `inline-block`                               | Inline-blokkelement.                                                                                  |
|                   | `flex`                                       | Flexbox container.                                                                                    |
|                   | `grid`                                       | Aktiverer CSS Grid.                                                                                   |
|                   | `hidden`                                     | Skjuler elementet.                                                                                    |
| **Position**      | `static`                                     | Standard posisjonering.                                                                               |
|                   | `fixed`                                      | Fester til viewport.                                                                                  |
|                   | `absolute`                                   | Absolutt posisjon i forhold til nærmeste posisjonerte foreldreelement.                                |
|                   | `relative`                                   | Relativ posisjon.                                                                                     |
|                   | `sticky`                                     | Posisjon i forhold til scroll.                                                                        |
| **Overflow**      | `overflow-auto`                              | Legger til scroll hvis nødvendig.                                                                     |
|                   | `overflow-hidden`                            | Skjuler overløpende innhold.                                                                          |
|                   | `overflow-scroll`                            | Alltid scroll.                                                                                        |
| **Z-index**       | `z-0`, `z-10`, `z-20`, ..., `z-50`          | Setter z-indeks. Høyere tall vises over lavere.                                                       |
| **🎨 Farger**     | `bg-{color}-{shade}`                         | Bakgrunnsfarge, eks: `bg-blue-500`.                                                                   |
|                   | `text-{color}-{shade}`                       | Tekstfarge, eks: `text-gray-700`.                                                                     |
| **Spacing**       | `p-{size}`, `px-{size}`, `py-{size}`         | Padding (p=alle, px=horisontal, py=vertikal), eks: `p-4`, `px-2`.                                     |
|                   | `m-{size}`, `mx-{size}`, `my-{size}`         | Margin (m=alle, mx=horisontal, my=vertikal), eks: `m-4`, `mx-2`.                                      |
| **Tekst og Font** | `text-{size}`                                | Tekststørrelse, eks: `text-lg`.                                                                       |
|                   | `font-{weight}`                              | Fontvekt, eks: `font-bold`, `font-light`.                                                             |
|                   | `text-center`, `text-left`, `text-right`     | Tekstjustering: senter, venstre, høyre.                                                               |
| **Responsivitet** | `{breakpoint}:{class}`                       | Responsiv prefix: `sm:`, `md:`, `lg:`, `xl:`, `2xl:` for mobile-first tilnærming.                     |
|                   | `sm:hidden`, `lg:flex`, `xl:text-center`     | Eksempel: `lg:flex` gjør elementet flex på store skjermer, `sm:hidden` skjuler på små skjermer.       |