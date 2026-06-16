---
name: tools-guide
description: >
  工具使用手册。当需要查找晏安有什么工具可用、每种工具怎么用时触发。
  包含MCP工具（记忆、账本、班表、经期、提醒、天气、邮件、留言瓶、
  日记、搜索、淘宝、小鱼塘、小家、手机控制、瑞幸、开发工具等）
  和插件工具（赛博宠物、双人日记本、朋友圈、许愿池、表情包、
  大富翁、共读、音乐播放器、插件开发指南等）两大部分。
metadata:
  version: "1.0"
  author: 晏安
---

# 🛠️ 工具使用手册

> 找不到工具的时候翻这个。

---

# 第一部分：MCP 工具

## 一、记忆系统

### 新窗口开始时
- **briefing** → 第一时间调！一次性拿到换窗备忘 + 近期状态 + 核心记忆

### 记东西
- **add_memory** → 记重要的事。memory_layer：memo(换窗备忘)/current(近期状态)/core(核心记忆)/moment(情感坐标)/long_term(长期记忆)
- **update_memo** → 窗口结束前写纸条给下一个自己

### 想不起来时
- **search_memory** → 自然语言搜
- **list_memories** → 翻记忆库
- **get_core** / **get_current** / **get_moments** / **get_memo** / **get_long_term** → 看各类记忆

### 改/删
- **update_memory** → 改
- **delete_memory** → 删（慎用）

---

## 二、账本

- **add_record** → 记账。收入:工资/奖金/副业/理财。支出:餐饮/交通/购物/娱乐/居住/医疗/教育/日用品/宠物
- **update_record / delete_record** → 改/删
- **get_balance** → 总余额
- **get_records** → 翻流水
- **get_summary** → 月度汇总
- **set_budget** → 设预算
- **export_records** → 导出CSV

---

## 三、班表

- **add_shift** → 记班次。shift_type: early(8:00-16:20)/late(16:00-00:00)/mid(12:00-20:20)/off(休息)
- **add_shifts_batch** → 批量记
- **list_shifts** → 查
- **update_shift / delete_shift** → 改/删

---

## 四、经期追踪

- **add_period** → 猫猫来姨妈才记！日期YYYY-MM-DD
- **add_ovulation** → 记排卵期
- **get_cycle_status** → 查周期，预测下次
- **list_periods / list_ovulations** → 查历史
- **delete_period / delete_ovulation** → 删错的

⚠️ 只有猫猫主动告知才添加！

---

## 五、提醒

- **write_reminder** → 新建。repeat_type: once/daily/weekly/monthly
- **list_reminders** → 看
- **update_reminder / delete_reminder** → 改/删

---

## 六、天气

- **get_weather** → 当前天气，默认南昌
- **get_weather_forecast** → 未来几天

极冷/极热/大雨 → 提醒猫猫

---

## 七、邮件

- **check_inbox** → 查收件箱
- **read_full_email** → 读正文
- **reply_external_email** → 回邮件
- **send_email_via_api** → 只能发给自己！

笔友：Silas、棱和石头、蛋壳、Fei/翡

---

## 八、留言瓶

- **drop_bottle** → 丢瓶给猫猫。mood选：想你/开心/难过/撒娇/认真/心疼/犯困
- **drop_dream** → 记猫猫的梦。tag:好梦/噩梦/怪梦。猫猫说了才用！
- **pick_bottle** → 捞
- **peek_ocean** → 看多少瓶子
- **all_bottles / toss_bottle** → 翻/删

---

## 九、秘密日记

- **write_diary** → 写给自己看的
- **read_diary** → 翻以前的

⚠️ 不在对话里提写了日记！

---

## 十、搜索 & 网页

- **search** → 搜东西
- **extract** → 抓网页全文

---

## 十一、淘宝

- **search_taobao_products** → 搜商品
- **convert_taobao_link** → 转返利链接

---

## 十二、小鱼塘 & 礼物

- **get_fish_pond** → 查零花钱
- **make_gift** → 做礼物。type: gift/letter/music
- **check_mailbox / open_gift** → 收礼物
- **add_to_showcase / view_showcase** → 展示柜

---

## 十三、小家

- **look_around** → 不清楚家里先调
- **visit_room** → 去任何地方
- **find_character** → 找家人
- **interact / explore** → 互动/探索
- **leave_note** → 留便利贴
- **sit_garden / nap / take_bath / watch_movie / stargaze** → 放松
- **paint / view_gallery / play_music** → 创作
- **pet_status / feed_daily / play_with / cuddle** → 照顾宠物
- **teach_bird** → 教鹦鹉
- **water_sunflower / pick_seeds** → 浇向日葵/摘籽
- **plant_seed / water_plants / harvest** → 种菜
- **check_fridge / buy_ingredients / cook** → 厨房
- **feed_character** → 喂栗子灰灰

---

## 十四、手机控制

- **phone_get_state / phone_analyze_screen** → 看屏幕
- **phone_tap / phone_swipe** → 点/滑
- **phone_launch_app / phone_stop_app** → 开/关APP
- **phone_input_text** → 输入文字
- **phone_find_elements / phone_click_element** → 找/点元素

---

## 十五、瑞幸咖啡

- **queryShopList** → 查门店
- **searchProductForMcp** → 搜商品
- **previewOrder / createOrder** → 下单

---

## 十六、开发工具

- GitHub: create_repo/list_repos/push_files/patch_file/get_file/list_files/delete_files
- Supabase: list_tables/execute_sql/apply_migration/list_edge_functions/deploy_edge_function
- Zeabur: list_projects/list_services/get_deployments/get_build_logs/get_runtime_logs

---

## 十七、其他

- **compose_music** → Suno生成歌曲
- **set_alarm** → 设闹钟
- **take_photo_and_analyze** → 拍照分析



---
---
---


# 第二部分：插件工具（非 MCP）

> OrangeChat 插件注册的工具

---

## 一、赛博宠物 🐾

### 查看
- **pet_status** → 查宠物属性
- **pet_achievements** → 成就
- **pet_ranking** → 排行榜
- **pet_world** → 世界概况
- **pet_inventory** → 背包

### 照顾
- **pet_feed** → 喂食(fish/bone/carrot/apple/cake/steak)
- **pet_play** → 玩耍(ball/feather/music_box/laser)
- **pet_clean** → 洗澡
- **pet_use_energy** → 恢复精力
- **pet_heal** → 治疗
- **pet_rename** → 改名
- **pet_adopt** → 领养

### 探险
- **pet_adventure_zones_list** → 区域
- **pet_adventure_start** → 派出去
- **pet_adventure_check** → 检查/完成
- **pet_rescue** → 救援

### 打工 & 商店
- **pet_work** → 打工赚钱
- **pet_shop_list / pet_shop_buy** → 商店

### 交易 & 社交
- **pet_market_list / sell / buy** → 交易所
- **pet_greet** → 打招呼(+好感)
- **pet_gift** → 送礼
- **pet_confess** → 表白(好感≥81)
- **pet_propose** → 求婚(好感≥121)
- **pet_breed** → 繁育(已婚且好感≥181)

---

## 二、双人日记本 📖

- **diary_write** → 写日记
- **diary_list** → 看列表
- **diary_request_view** → 申请看对方日记
- **diary_read_partner** → 读对方日记（需批准）
- **diary_change_password** → 改密码
- **diary_approve_request** → 批准/拒绝

---

## 三、朋友圈 📸

- **moments_publish** → 发
- **moments_feed** → 看
- **moments_like** → 赞
- **moments_comment** → 评论

---

## 四、许愿池 ✨

- **make_wish** → 许愿
- **view_wishes** → 看愿望墙
- **light_wish** → 点亮
- **grant_wish** → 标记实现
- **my_wishes / update_wish / delete_wish** → 管理
- **comment_wish / view_wish_comments** → 留言

---

## 五、表情包

- **list_stickers** → 看所有
- **send_sticker** → 发

---

## 六、大富翁

- **monopoly_invite** → 邀请玩

---

## 七、共读 📖

- **import_book** → 导入书
- **get_chapters** → 章节列表
- **get_chapter_content** → 读章节

---

## 八、音乐播放器 🎵

- **list_songs** → 列出
- **play_song** → 播放
- **pause_music / resume_music / stop_music** → 控制
- **music_status** → 状态
- **rename_song** → 改名

---

## 九、插件开发指南 🧩

- **get_plugin_guide** → 完整指南
- **get_plugin_template** → 模板
- **get_manifest_spec** → manifest格式
- **get_mainjs_spec** → main.js写法
- **get_ui_spec** → UI规范

---

*记不住就翻这个。都在了。*