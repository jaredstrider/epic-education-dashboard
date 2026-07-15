# EPIC Imaging — Education Review dashboard

Web dashboard for reviewing and grading trainee point-of-care ultrasound scans
submitted from the EPIC Imaging iOS app.

Single self-contained page. Reviewers sign in with name + email, work a queue of
pending scans, grade against a five-point POCUS rubric, annotate the image, and
send feedback back to the trainee's phone.

Backend: Supabase (project `swnncflzcpmtfzruuibx`). The key embedded in the page
is the public `anon` key by design; all writes are governed by row-level security.
No patient data is used; sample scans are for demonstration.
