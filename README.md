# table-fixed-head
表格头部或左侧固定
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>new document</title>
<meta charset="utf-8"/>
<meta http-equiv="content-type" content="text/html;charset=utf-8">
<script type="text/javascript" src="js/jquery.min.js"></script>
<script type="text/javascript" src="js/TableScroll.js"></script>
</head>
<body>
 <table
  style="border-bottom-color: black; border-top-color: black; width: 1000px; color: #000000; border-right-color: black; font-size: medium; border-left- color: black"
  id="MyTable" border="1" cellspacing="0" cellpadding="0">
  <thead>
   <tr>
    <th style="text-align: center; width: 80px" rowspan="3">姓名</th>
    <th style="text-align: center; width: 80px" rowspan="3">班级</th>
    <th style="text-align: center" colspan="10">成绩</th>
   </tr>
   <tr>
    <th style="text-align: center" colspan="3">主科</th>
    <th style="text-align: center" colspan="3">文科</th>
    <th style="text-align: center" colspan="3">理科</th>
    <th style="text-align: center; width: 80px" rowspan="2">总分</th>
   </tr>
   <tr>
    <th style="text-align: center; width: 80px">语文</th>
    <th style="text-align: center; width: 80px">数学</th>
    <th style="text-align: center; width: 80px">英语</th>
    <th style="text-align: center; width: 80px">政治</th>
    <th style="text-align: center; width: 80px">历史</th>
    <th style="text-align: center; width: 80px">地理</th>
    <th style="text-align: center; width: 80px">物理</th>
    <th style="text-align: center; width: 80px">化学</th>
    <th style="text-align: center; width: 80px">生物</th>
   </tr>
  </thead>
  <tbody>
   <!-- 数据行 -->
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
   <tr>
    <td>学生32</td>
    <td>班级1</td>
    <td>29</td>
    <td>25</td>
    <td>146</td>
    <td>28</td>
    <td>79</td>
    <td>73</td>
    <td>47</td>
    <td>8</td>
    <td>91</td>
    <td>526</td>
   </tr>
  </tbody>
 </table>
</body>
</html>
