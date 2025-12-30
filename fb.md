Flex Box:

1. Flex-container

  - justify-content: - căn flex-items theo trục chính(main axis)
Value:
  + flex-start (default)
  + flex-end
  + center
  + space-between
  + space-around
  + space-evenly (khoảng cách bằng nhau)

  - align-items: - căn theo trục phụ(cross axis)
Value:
  + flex-start 
  + flex-end 
  + center 
  + stretch (default)
  + baseline 

  - flex-wrap: - xuống dòng hay không
Value:
  + nowrap: không xuống dòng (default)
  + wrap: xuống dòng (cross start trên -> cross end dưới)
  + wrap-reverse: xuống dòng ngược (coss end trên <- cross start dưới)

  - align-content: - dồn nhiều hàng theo trục phụ(cross axis)
  ❗ Chỉ có tác dụng khi flex-wrap: wrap
 Value:
  + flex-start 
  + flex-end 
  + center 
  + space-between 
  + space-around 
  + space-evenly

  - flex-direcotion: - hướng trục chính (main axis)
Value:
  + row (default) main axis ->
  + row-reverse (main end trái - main start phải -
  chiều main axis <-)
  + column (chiều main axis ↓ - chiều cross axis ->)
  + colum-reverse (chiều main axis ↑ - chiều cross axis ->)

  - flex-flow: = flex-wrap + flex-direction

2. flex-item:

  - align-self: -căn riêng 1 item
Value:
  + flex-start
  + flex-end
  + center
  + baseline
  + stretch (default)

  - flex-grow: - độ giãn

  - flex-shrink: - độ co
Value:
  + 1 : co khi thiếu chỗ (default)
  + 0 : không co  

  - flex-basis: - kích thước ban đầu (set main size item theo trục main axis)
Value:
  + auto (theo width/height)
  + content (theo nội dung)
  + px
  + %

  - flex: = flex-grow + flex shrink + flex-basis
    
  - order: - thay đổi thứ tự các items
Value:
  + 0 (default)
  + số âm (đứng trước)
  + số dương (đứng sau)