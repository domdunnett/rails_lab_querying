1. TowTruck.all
2. Vehicle.find_by(id: 3)
3. Vehicle.find_by(vin: "D0985DF1593A350A4")
4. Vehicle.order(:acquired_at)
5. Vehicle.order(:acquired_at).find_by(color: "silver")
6. Vehicle.where(category: "car", color: "red", make: "Honda")
7. Vehicle.where(category: "motorcycle").count
8. Vehicle.where(released_at: nil).count
9. TowTruck.where("mileage > 200,000")
10. 
11.
12. Vehicle.order(:fee).first(3)