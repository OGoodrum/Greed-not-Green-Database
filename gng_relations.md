Campaign(campaignID, name, startDate, endDate)

Event(campaignID, date, location, startTime, endTime)

Volunteer(volunteerID, name, tier)

Participates(volunteer, campaignID, date, location)

Fund(fundID, date, time, amount)

Fundraised(fund, campaign)

Cost(fund, campaign)

Office(address, rent)

Rent Payement(office, fund)

Employee(employeeID, name, title, salary)

Paid(fund, employee)

Works At(employee, office)

Donor(donorID, name)

Gives To(donor, fund)

Member(memberID, name)

Supports(member, campaign)

Website Posting(campaignID, date, time, author)
