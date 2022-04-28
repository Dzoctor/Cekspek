# Computer marketplace using benchmarking feature - phase_1

## algo
user nyari komputer dari keyword -> user milih komputer pake filter -> user beli komputer yg cocok
(revebue dr nginstall software ke pc)

## flow chart
### 1
- input -> game_keyword (just top games)
- process -> game_spec (min-max) -benchmark (realtime_test, 3d_mark, benchmark_comparasion)- pc_spec (cpu, gpu, ram)
- output -> pc_item (rating, possibility, recommendation)

### 2
- input -> filter_keyword (condition, price, )
- process -> filter_keyword -check- pc_item
- output -> pc_item

### 3
- input -> buy_pc
- process -> buy_pc -request- pc_item
- output -> pc_item

## pseudo-code
1. varible : game_keyword, game_spec, pc_spec filter_keyword, buy_pc, pc_item
2. function : benchmark, spec, request
3. return : pc_item

# Computer marketplace using benchmarking feature - phase_2
## update
1. user ngesearch pakek semua keyword software (app_software ,sys_software, prog_software)
2. user bisa make multiple keyword (keyword_pack)
3. user punya prioritas untuk nemuin komputer terbaru pertama kali (first_served)
4. user bisa ngelihat review real-time test game
3. user bebas milih komponen komputer (build_maker, build_upgrader, part_replacer)

# Computer marketplace using benchmarking feature - phase_3
## update
1. company bisa ngebeli data user yang milih spec komputernya
2. afiliasi ke streamer untuk promosi specnya
3. use bisa ngejual spec komputer lamanya
