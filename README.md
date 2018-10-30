public boolean answerCell(boolean isMorning, boolean isMom, boolean isAsleep) {
  
  if(isAsleep == true){
    return false;
  }
  
  else if(isMorning == true){
    if(isMom == true){
      return true;
    }
    else{
      return false;
    }
  }
  
  return true;
  
}
