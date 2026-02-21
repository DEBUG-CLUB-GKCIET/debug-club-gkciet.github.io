---
layout: page
title: Join Us
permalink: /join/
full_width: true
---

<!-- HEADER -->
<!-- HEADER -->
<section class="py-5 position-relative overflow-hidden" style="min-height: 90vh; display: flex; align-items: center; justify-content: center;">
    
    <!-- Background Decor -->
    <div class="position-absolute top-0 start-0 w-100 h-100" style="z-index: 0; pointer-events: none;">
         <div class="position-absolute top-50 start-50 translate-middle" style="width: 600px; height: 600px; background: radial-gradient(circle, rgba(0, 229, 153, 0.03) 0%, transparent 70%);"></div>
         <div class="code-overlay opacity-10" style="background-image: url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PCEtLSB5b3VyIHBhdHRlcm4gaGVyZSAtLT48Y2lyY2xlIGN4PSIyIiBjeT0iMiIgcj0iMSIgZmlsbD0iIzMzMyIgLz48L3N2Zz4=');"></div>
    </div>

    <div class="container position-relative z-1 fade-in-up">
        <div class="glass-card p-0 mx-auto rounded-5 overflow-hidden shadow-lg" style="max-width: 800px;">
            
            <!-- Terminal Header -->
            <div class="border-bottom p-3 d-flex align-items-center justify-content-between" style="background: rgba(0,0,0,0.02);">
                <div class="d-flex gap-2">
                    <div class="rounded-circle bg-danger" style="width: 12px; height: 12px;"></div>
                    <div class="rounded-circle bg-warning" style="width: 12px; height: 12px;"></div>
                    <div class="rounded-circle bg-success" style="width: 12px; height: 12px;"></div>
                </div>
                <div class="font-monospace small">system_status.log</div>
                <div></div>
            </div>

            <div class="p-5 text-center">
                <div class="mb-4 position-relative d-inline-block">
                    <!-- Rotating Ring -->
                    <div class="position-absolute top-50 start-50 translate-middle border border-2 border-dashed opacity-25 rounded-circle" style="width: 100px; height: 100px; animation: spin 10s linear infinite; border-color: currentColor;"></div>
                    
                    <!-- Icon -->
                    <div class="position-relative rounded-circle p-4 shadow-sm" style="background: rgba(0,0,0,0.02); border: 1px solid rgba(0,0,0,0.1);">
                        <i class="fas fa-tools fa-3x" style="color: #2563EB;"></i>
                    </div>
                </div>

                <h1 class="display-5 fw-bold mb-2">System Upgrade</h1>
                <p class="font-monospace mb-4"><span class="spinner-border spinner-border-sm me-2"></span><span style="color: #2563EB;">Maintenance Mode Active</span></p>
                
                <div class="alert rounded-3 p-4 mb-5 mx-auto shadow-sm" style="max-width: 600px; border: 1px solid rgba(37, 99, 235, 0.3); background: rgba(37, 99, 235, 0.05);">
                    <div class="d-flex align-items-start gap-3 text-start">
                        <i class="fas fa-info-circle mt-1" style="color: #2563EB;"></i>
                        <p class="mb-0 font-monospace small fw-bold" style="line-height: 1.6;">
                            "This page is under maintenance, Contact existing club members to become a member of DEBUG"
                        </p>
                    </div>
                </div>

                <div class="d-flex flex-column flex-sm-row justify-content-center gap-3">
                    <a href="/team/" class="btn btn-primary rounded-pill px-5 py-3 fw-bold">
                        <i class="fas fa-users me-2"></i> Contact Club Members
                    </a>
                    <a href="/" class="btn btn-outline-light rounded-pill px-5 py-3 fw-bold">
                        Return Home
                    </a>
                </div>
            </div>
            
            <!-- Terminal Footer -->
            <div class="p-3 border-top" style="background: rgba(0,0,0,0.02);">
                <div class="row align-items-center">
                    <div class="col-6 text-start">
                        <span class="font-monospace small">STATUS: <span style="color: #EAB308;">MAINTENANCE</span></span>
                    </div>
                    <div class="col-6 text-end">
                        <span class="font-monospace small">ERR_CODE: 503</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<style>
@keyframes spin { 100% { transform: translate(-50%, -50%) rotate(360deg); } }
</style>
