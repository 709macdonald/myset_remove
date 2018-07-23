# myset_remove

var myset = [1, 2, 3, 4, 5];
var nope = 3;

function remove(myset_remove, deletenum){

var counter = 0;
var newsum = [];

while (counter < myset_remove.length){
  if(myset_remove[counter] == deletenum) {
      counter++;
      continue;
    }
      else {
      newsum.push (myset_remove[counter]);
      counter++;
    }
  }

console.log(newsum)

}

remove(myset,nope);
