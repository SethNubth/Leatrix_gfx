# Leatrix_gfx
Fps Lwo WoLK 3.3.5 

--                                                                                           --
--                                       Leatrix Gfx 2.15                                    --
--                          PURE LUA V1.0 - 4 LOCALES + FIX                                  --
--                                                                                           --
--                            ENGLISH / РУССКИЙ / ESPAÑOL / PORTUGUÊS                       --
--                                                                                           --


[ENGLISH]
What is it?

Leatrix Gfx is a small addon to boost FPS in WotLK 3.3.5a. Same original design from 2009.

What was fixed?

1. FIXED: fpscap:SetValue(value) error line 151
   - Now uses tonumber(LeaGfxLC["fpscap"]) or 120
   - Never nil, always a valid number

2. ADDED: 4 Languages auto-detect
   - enUS / enGB -> English
   - ruRU -> Русский
   - esMX / esES -> Español
   - ptBR -> Português
   - Uses GetLocale() - no extra folders needed

3. KEPT: 100% original look /gfx panel
   - Same checkboxes, sliders, positions as 2.15 original
   - Original 12.3kB code preserved

Installation:

1. Delete old Interface\AddOns\leatrix_gfx\
2. Delete WTF\Account\YOURACCOUNT\SavedVariables\Leatrix_Gfx.lua
3. Copy new leatrix_gfx folder to Interface\AddOns\
4. /gfx in game to configure

Commands:

/gfx - Open panel
/gfx reload - Reload UI + RestartGx


[РУССКИЙ]
Что это?

Leatrix Gfx - маленький аддон для повышения FPS в WotLK 3.3.5a. Тот же дизайн 2009 года.

Что исправлено?

1. ИСПРАВЛЕНО: Ошибка fpscap:SetValue(value) строка 151
   - Теперь tonumber(LeaGfxLC["fpscap"]) or 120
   - Никогда не nil, всегда число

2. ДОБАВЛЕНО: 4 языка автоопределение
   - Клиент сам выбирает язык

3. СОХРАНЕН: 100% оригинальный вид панели /gfx

Установка:

1. Удалить старый Interface\AddOns\leatrix_gfx\
2. Удалить WTF\...\Leatrix_Gfx.lua
3. Скопировать новый leatrix_gfx
4. /gfx в игре


[ESPAÑOL]
¿Qué es?

Leatrix Gfx es un addon pequeño para subir FPS en WotLK 3.3.5a. Mismo diseño original 2009.

¿Qué se reparó?

1. ARREGLADO: Error fpscap:SetValue(value) linea 151
   - Ahora usa tonumber(LeaGfxLC["fpscap"]) or 120
   - Nunca nil, siempre número válido

2. AÑADIDO: 4 Idiomas auto-detectable
   - El cliente detecta solo el idioma

3. CONSERVADO: 100% apariencia original panel /gfx

Instalación:

1. Borra viejo Interface\AddOns\leatrix_gfx\
2. Borra WTF\Account\TU CUENTA\SavedVariables\Leatrix_Gfx.lua
3. Copia nuevo leatrix_gfx a Interface\AddOns\
4. /gfx en el juego para configurar

Comandos:

/gfx - Abrir panel
/gfx reload - Recargar UI


[PORTUGUÊS]
O que é?

Leatrix Gfx é um addon pequeno para aumentar FPS no WotLK 3.3.5a. Mesmo design original 2009.

O que foi corrigido?

1. CORRIGIDO: Erro fpscap:SetValue(value) linha 151
   - Agora usa tonumber(LeaGfxLC["fpscap"]) or 120
   - Nunca nil, sempre número válido

2. ADICIONADO: 4 Idiomas auto-detecção
   - Cliente detecta sozinho o idioma

3. MANTIDO: 100% aparência original painel /gfx

Instalação:

1. Delete antigo Interface\AddOns\leatrix_gfx\
2. Delete WTF\...\Leatrix_Gfx.lua
3. Copie novo leatrix_gfx
4. /gfx no jogo


CREDITS:

Original Author: Leatrix (2009)
Fix + 4 Locales PURE LUA: GOD + Meta AI
Version: 2.15-ORIGINAL-4LOCALES-FIX
PURE LUA V1.0 - No external libs - ACP Safe - WotLK 3.3.5a
