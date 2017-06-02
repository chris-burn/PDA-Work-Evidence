### Testing task 1 code:

  Carry out static testing on the code below.  
  Read through the code.  Highlight any errors you can see without correcting them.

 
def func1 val     #no brackets round (val) property
  if val = 1
  return true
  else
  return false
  end
end
  
dif max a b       #spelling error, *def
  if a > b
      return a 
  else
  b                 # return missing
  end 
end 
end                   # additional end
  
def looper 
  for i in 1..10
  puts i
  end
end                   #incorrect end statement placement ?
 
failures = 0 
 
if looper == 10 
  puts "looper passed"
else
  puts "looper failed"
  failures = failures + 1     # += 1 ??
                              #no end statement  
  

                              # single = , no sum involved?    # to be included in func1 method?               
if func1(3) == false         
  puts "func1(3) passed"
else
  puts "func1(3) failed"
  failures = failures + 1      # += 1 ?
end 
 
  
if max(100,1) == 100  
  puts "max(100,1) passed"
else
  puts "func1(3) failed"      # incorrect method failure message?
  failrues = failures + 1     #spelling mistake     # += 1 ??
end

  
if failures                 # no definition on variable of calc pass/failure, "if failures > 0" ?
  puts "Test Failed"
else
  puts "Test Passed"
end


