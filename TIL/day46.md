# DAY46

## 1. 수업내용
#### 1. @ModelAttribute 사용법 (상단의 카테고리가 남아있게 함)

```
@ModelAttribute("catelist")
	public List<CateVO> makemenu(){
		//System.out.println("makemenu");
		List<CateVO> catelist = null;
		try {
			catelist = catebiz.getmain();
		} catch (Exception e) {
			e.printStackTrace();
		}
		return catelist;
	}
  ```
  
##  2. 새로운 기능을 추가한 후에는
#### 1. mapper.xml --> Mapper --> Biz --> Test(test까지 반드시)
