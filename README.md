# St. Petersburg semantic metro map

* spb.trp — описание схемы метро в формате программы [pMetro], версия от 15.01.2018 г.
* spb.json:
  - то же описание, но в JSON
  - добавлен параметр `StationIDs` — id станций в том же порядке, что и названия
  - секция `Transfers` упрощена
  - удалены строящиеся станции
* spb.svg, spb.png — схема Лебедева, версия 0.5.1
* master.svg:
  - линии взяты из схемы Лебедева
  - подписи сделаны элементами `<text>`
  - станции сгруппированы с подписями в `<g id="{station_id}">`
  - перегонам добавлен `id="{station1_id}_{station2_id}"`
  - можно добавить фон с дополнительной инфой (реки, острова, вокзалы, POI) из оригинальной схемы
* simple.svg:
  - станции расположены компактнее, но фон из оригинальной схемы добавить не выйдет

[pMetro]: http://pmetro.su/