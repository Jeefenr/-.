print "Введіть перше число: "
num1 = gets.chomp.to_f

print "Введіть друге число: "
num2 = gets.chomp.to_f

dodavannya = num1 + num2
vidnimannya = num1 - num2
mnozhennya = num1 * num2
dilennya = num1 / num2

puts "\nРезультати:"
puts "#{num1} + #{num2} = #{dodavannya}"
puts "#{num1} - #{num2} = #{vidnimannya}"
puts "#{num1} * #{num2} = #{mnozhennya}"
puts "#{num1} / #{num2} = #{dilennya}"
