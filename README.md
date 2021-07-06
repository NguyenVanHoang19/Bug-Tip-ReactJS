# Bug-Tip-ReactJS

Map data a -> b
const a = [
          {
            ho: "Nguyen",
            ten: "a"
          }
        ];
const b = [
          {
            ho: "Nguyen",
            ten: "a",
            ho_ten: "Nguyen a"
          }
      ];
      
--> 
a = a.map(value => ({
  ...value,
  ho_ten: value.ho + ' ' + value.ten
}));
