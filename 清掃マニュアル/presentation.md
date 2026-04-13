---
marp: true
theme: default
paginate: true
size: 16:9
style: |
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;700&family=Playfair+Display:ital,wght@0,600;1,600&display=swap');

  section {
    font-family: 'Noto Sans JP', sans-serif;
    padding: 0;
    margin: 0;
    background-color: white;
    color: #0f172a;
    display: flex;
    flex-direction: column;
  }

  /* 顶部导航条 */
  .header-bar {
    background: #0f172a;
    padding: 15px 40px;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 50px;
  }

  /* 区域标签 */
  .zone-tag {
    background: #c5a880;
    color: white;
    padding: 3px 12px;
    font-size: 14px;
    font-weight: bold;
    letter-spacing: 0.1em;
  }

  /* 图片占位符样式 */
  .photo-main {
    background-color: #f1f5f9;
    border: 2px solid #e2e8f0;
    height: 380px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #94a3b8;
    font-weight: bold;
    font-size: 18px;
    position: relative;
  }
  .photo-detail {
    background-color: #f8fafc;
    border: 1px solid #e2e8f0;
    height: 110px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    color: #94a3b8;
    text-align: center;
    padding: 5px;
  }
  .photo-ng {
    background-color: #fef2f2;
    border: 2px solid #ef4444;
    height: 140px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    padding: 10px;
  }
  .ng-label {
    position: absolute;
    top: 0; left: 0;
    background: #ef4444;
    color: white;
    font-weight: bold;
    font-size: 11px;
    padding: 2px 8px;
  }

  /* 描述框 */
  .desc-box {
    background: #f8fafc;
    padding: 12px;
    border-left: 4px solid #c5a880;
    font-size: 14px;
    margin-top: 10px;
  }

  /* 表格 */
  table { width: 100%; font-size: 12px; border-collapse: collapse; }
  th { background: #0f172a; color: white; padding: 6px; text-align: left; }
  td { padding: 4px 6px; border-bottom: 1px solid #e2e8f0; background: white; }

  /* 标题页样式 */
  section.cover { flex-direction: row; }
  .sidebar {
    width: 320px;
    background-color: #0f172a;
    padding: 40px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .main-content {
    flex-grow: 1;
    padding: 60px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .accent { color: #c5a880; }
  .serif-en { font-family: 'Playfair Display', serif; }
---

<div class="sidebar">
  <div>
    <h3 class="serif-en" style="color: #c5a880; font-style: italic; font-size: 32px; margin: 0;">Tokyo H.C.</h3>
    <p style="font-size: 10px; letter-spacing: 0.4em; opacity: 0.4; text-transform: uppercase;">Internal Standards v3.0</p>
  </div>
  <p style="font-size: 10px; opacity: 0.3; line-height: 1.5;">© 2026 Tokyo Hospitality Clean<br>Property: 民宿ホテルB<br>Room: Type A (3 Bedroom)</p>
</div>
<div class="main-content">
  <span style="border: 1px solid #c5a880; color: #c5a880; padding: 2px 10px; font-size: 12px; width: fit-content; margin-bottom: 30px;">内部管理用・持出厳禁</span>
  <h1 style="font-size: 70px; margin: 0; line-height: 1.1;">民宿ホテルB<br><span class="accent" style="font-weight: 300; font-style: italic;">Type A (3BR)</span></h1>
  <p style="font-size: 24px; color: #94a3b8; letter-spacing: 0.2em; margin-top: 10px;">エリア別・復元マニュアル手册</p>
  <div style="width: 120px; height: 4px; background: #c5a880; margin: 40px 0;"></div>
  <p style="font-style: italic; color: #64748b; font-size: 14px;">"标准化是规模化的唯一基石。"</p>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">01 総合：基本運用ルール</h2>
  <span class="serif-en" style="font-size: 12px; opacity: 0.5;">OPERATIONAL PROTOCOL</span>
</div>
<div style="padding: 30px 40px; display: grid; grid-template-columns: 1fr 2fr; gap: 40px;">
  <div style="display: flex; flex-direction: column; gap: 20px;">
    <div>
      <h4 style="border-bottom: 1px solid #c5a880; font-size: 14px; padding-bottom: 5px;">🔑 鍵・開門 (Entry)</h4>
      <p style="font-size: 12px; display: flex; justify-content: space-between; margin: 5px 0;"><span>101/102 (A)</span> <b>1234#</b></p>
      <p style="font-size: 12px; display: flex; justify-content: space-between; margin: 5px 0;"><span>Entrance</span> <b>*9999#</b></p>
    </div>
    <div style="background: #f8fafc; padding: 15px;">
      <h4 style="border-bottom: 1px solid #c5a880; font-size: 14px; padding-bottom: 5px;">🕒 時間管理 (Schedule)</h4>
      <p style="font-size: 12px; margin: 5px 0;"><b>10:00</b> - 清掃開始</p>
      <p style="font-size: 12px; margin: 5px 0;"><b>14:30</b> - 清掃・检查完了</p>
      <p style="font-size: 12px; margin: 5px 0;"><b>15:00</b> - ゲスト入室</p>
    </div>
  </div>
  <div style="background: #f8fafc; padding: 25px; border-radius: 8px;">
    <h4 style="font-size: 14px; margin-bottom: 15px;">🙇 接客礼仪 (Hospitality Manner)</h4>
    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
      <div class="photo-main" style="height: 180px; font-size: 12px;">[图：30度鞠躬标准姿势]</div>
      <div style="display: flex; flex-direction: column; gap: 10px;">
        <div style="background: white; padding: 10px; border-left: 4px solid #c5a880;">
          <p style="font-weight: bold; font-size: 12px;">见到客人</p>
          <p style="font-size: 11px; color: #64748b;">停下动作，微笑点头：「こんにちは」</p>
        </div>
        <div style="background: white; padding: 10px; border-left: 4px solid #c5a880;">
          <p style="font-weight: bold; font-size: 12px;">客人离开</p>
          <p style="font-size: 11px; color: #64748b;">侧身礼让：「ありがとうございます」</p>
        </div>
        <p style="color: #ef4444; font-size: 10px; font-weight: bold;">※ 严禁在公共区域大声喧哗或使用方言。</p>
      </div>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">02 玄関・廊下</h2>
  <span class="zone-tag">ZONE: ENTRANCE</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 2fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main">[大图：玄关整理后第一视角全景]</div>
    <div class="desc-box"><b>玄关要点：</b>地板必须光亮无印迹。拖鞋架按“成人L-成人M-儿童”顺序从左往右靠齐。</div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-detail">[细节图：拖鞋Logo及间距]</div>
    <div class="photo-detail">[细节图：伞架及门后挂钩]</div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 12px; text-align: center;">门缝处有沙尘堆积<br>(必须扫除排查)</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">03 キッチン P1：配置・食器</h2>
  <span class="zone-tag">ZONE: KITCHEN</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 1.5fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main">[大图：厨房台面整体标准对图]</div>
    <div class="desc-box"><b>餐具标准：</b>所有杯具手柄方向一致。调味品标签完全正向朝外。</div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 10px;">
    <div class="photo-detail" style="height: 130px;">[细节图：抽屉内餐具整齐排列图]</div>
    <div class="photo-detail" style="height: 130px;">[细节图：橱柜内锅具摆放位置]</div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 12px;">碗筷上有未擦干的水渍</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">04 キッチン P2：家電・シンク</h2>
  <span class="zone-tag">ZONE: KITCHEN</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main" style="height: 380px;">[大图：水槽与沥水架细节图]</div>
    <div class="desc-box"><b>水槽标准：</b>抛光至无任何白斑。排水口提笼必须拿出刷洗并喷洒酒精。</div>
  </div>
  <div style="display: grid; grid-template-columns: 1fr 1fr; grid-template-rows: 1fr 1.5fr 1.5fr; gap: 10px;">
    <div class="photo-detail" style="height: auto;">[冰箱内无残留物]</div>
    <div class="photo-detail" style="height: auto;">[微波炉内壁油渍]</div>
    <div class="photo-ng" style="grid-column: span 2; height: auto;">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 12px;">电饭锅盖边缘有残留米屑</p>
    </div>
    <div class="photo-ng" style="grid-column: span 2; height: auto;">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 12px;">垃圾桶盖子表面有指纹</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">05 リビングルーム</h2>
  <span class="zone-tag">ZONE: LIVING</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 2fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main">[大图：客厅沙发与茶几还原图]</div>
    <div class="desc-box"><b>客厅重点：</b>沙发靠垫必须呈“V型”凹陷或平直蓬松。地毯吸尘需无毛发。</div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-detail" style="height: 120px;">[细节：遥控器按长短垂直排列]</div>
    <div class="photo-ng" style="height: 120px;">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 11px;">沙发缝隙中有客人遗留硬币/垃圾</p>
    </div>
    <div class="photo-detail" style="height: 120px;">[细节：茶几桌面指纹排查]</div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">06 寝室 01 (主寝室)</h2>
  <span class="zone-tag">ZONE: BDR 01</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 1.5fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main">[大图：主卧铺床完成图]</div>
    <div class="desc-box"><b>床铺标准：</b>被套呈“豆腐块”立体感，绷紧。床头柜备品按“左水右杯”排列。</div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 8px;">
    <div class="photo-detail">[细节：枕头摆放角度与中心对齐]</div>
    <div class="photo-detail">[细节：床尾凳/抱枕位置]</div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 11px;">床底靠墙处有灰尘团 (必须吸尘)</p>
    </div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 11px;">衣架数量不足/挂向不一</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">07 寝室 02 (洋室)</h2>
  <span class="zone-tag">ZONE: BDR 02</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 1.5fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main" style="height: 450px;">[大图：次卧卧室整体对图]</div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-detail">[细节：阅读灯/充电线收纳]</div>
    <div class="photo-detail">[细节：窗台边角除尘]</div>
    <div class="photo-ng" style="height: 200px;">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 14px; text-align: center;">空调滤网积灰<br>(每月必须检查一次)</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">08 寝室 03 (和室/多床)</h2>
  <span class="zone-tag">ZONE: BDR 03</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 1.5fr 1fr; gap: 20px;">
  <div>
    <div class="photo-main" style="height: 450px;">[大图：第三卧室/多床位布局图]</div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-detail">[细节：多床间的间距统一]</div>
    <div class="photo-detail">[细节：榻榻米/地板接缝除尘]</div>
    <div class="photo-ng" style="height: 200px;">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 14px; text-align: center;">床头靠垫有压痕未恢复</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">09 トイレ・浴室</h2>
  <span class="zone-tag">ZONE: SANITARY</span>
</div>
<div style="padding: 25px 40px; display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px;">
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-main" style="height: 300px; font-size: 14px;">[图：马桶与地面全景]</div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 11px;">马桶盖连接处有黄迹</p>
    </div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-main" style="height: 300px; font-size: 14px;">[图：浴室镜面与洗手台]</div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 11px;">地漏处残留毛发/黏液</p>
    </div>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-main" style="height: 300px; font-size: 14px;">[图：浴缸与洗浴备品]</div>
    <div class="photo-ng">
      <div class="ng-label">NG</div>
      <p style="color: #ef4444; font-weight: bold; font-size: 11px;">备品瓶底有霉点或积水</p>
    </div>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">10 その他設備・備品</h2>
  <span class="zone-tag">ZONE: OTHERS</span>
</div>
<div style="padding: 30px 40px; display: grid; grid-template-columns: 1fr 1fr; gap: 40px;">
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-main" style="height: 350px;">[图：阳台/窗帘/投影仪位置]</div>
    <p style="font-size: 14px; color: #64748b; line-height: 1.6;">
      ● 投影仪：镜头需除尘，幕布需卷收整齐。<br>
      ● 窗帘：左右对接处必须完美闭合，无缝隙。
    </p>
  </div>
  <div style="display: flex; flex-direction: column; gap: 15px;">
    <div class="photo-main" style="height: 350px;">[图：洗衣机及洗剂存放]</div>
    <p style="font-size: 14px; color: #64748b; line-height: 1.6;">
      ● 洗衣机：洗剂盒擦净残液，盖子保持微启。<br>
      ● 阳台：地面扫净，无客人物品残留。
    </p>
  </div>
</div>

---

<div class="header-bar">
  <h2 style="font-size: 20px; margin:0;">FINAL CHECKLIST | 最終点検確認表</h2>
</div>
<div style="padding: 25px 40px;">
  <div style="display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 20px;">
    <table>
      <tr><th colspan="2">1. 入口・キッチン</th></tr>
      <tr><td>玄关地板无灰尘</td><td style="text-align:center;">□</td></tr>
      <tr><td>冰箱内壁清洁无味</td><td style="text-align:center;">□</td></tr>
      <tr><td>微波炉/电饭锅内外净</td><td style="text-align:center;">□</td></tr>
      <tr><td>碗筷干燥且Logo一致</td><td style="text-align:center;">□</td></tr>
      <tr><td>水槽抛光无水渍</td><td style="text-align:center;">□</td></tr>
    </table>
    <table>
      <tr><th colspan="2">2. 寝室・リビング</th></tr>
      <tr><td>被子床单平整无皱</td><td style="text-align:center;">□</td></tr>
      <tr><td>全床粘毛器除毛完成</td><td style="text-align:center;">□</td></tr>
      <tr><td>遥控器/备品对图完成</td><td style="text-align:center;">□</td></tr>
      <tr><td>床底/沙发手电筒检查</td><td style="text-align:center;">□</td></tr>
      <tr><td>衣柜内衣架排列整齐</td><td style="text-align:center;">□</td></tr>
    </table>
    <table>
      <tr><th colspan="2">3. 水回り・設備</th></tr>
      <tr><td>马桶底座/缝隙无垢</td><td style="text-align:center;">□</td></tr>
      <tr><td>排水口毛发彻底清理</td><td style="text-align:center;">□</td></tr>
      <tr><td>洗浴瓶身Logo正向</td><td style="text-align:center;">□</td></tr>
      <tr><td>投影仪/遥控功能测试</td><td style="text-align:center;">□</td></tr>
      <tr><td>空调/灯光/门锁关闭</td><td style="text-align:center;">□</td></tr>
    </table>
  </div>

  <div style="margin-top: 30px; background: #0f172a; padding: 25px; border-radius: 8px; color: white; display: flex; justify-content: space-between; align-items: center;">
    <div>
      <p style="color: #c5a880; font-weight: bold; font-size: 14px; margin: 0 0 5px 0;">【完了報告義務】</p>
      <p style="font-size: 12px; margin: 0;">全区域拍摄完成后上传至管理系统。インスペクター确认通过后方可撤场。</p>
    </div>
    <div style="text-align: right;">
      <p class="serif-en accent" style="font-size: 28px; font-style: italic; margin: 0;">Excellence through Discipline.</p>
    </div>
  </div>
</div>